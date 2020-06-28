# Use the official image as a parent image.
FROM php:7.4.7-apache

# Set the working directory.
WORKDIR /usr/src/app

# Copy the file from your host to your current location.
COPY /var/www/html/ .


# Inform Docker that the container is listening on the specified port at runtime.
EXPOSE 8080

# Run the command inside your image filesystem.
# RUN npm install

# Run the specified command within the container.
# CMD [ "npm", "start" ]

# Copy the rest of your app's source code from your host to your image filesystem.
# COPY . .