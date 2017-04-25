# Adds wp-cli to the offical WordPress image
FROM wordpress:latest
MAINTAINER Russ McKendrick <russ@mckendrick.io>

# Install the packages we need to run wp-cli
RUN apt-get update && apt-get install -y sudo less mysql-client && curl -o /bin/wp-cli.phar https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar

# Copy the wrapper for wp-cli and set the correct execute permissions
COPY wp /bin/wp
RUN chmod 755 /bin/wp-cli.phar /bin/wp

# Clean up the installation files
RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*