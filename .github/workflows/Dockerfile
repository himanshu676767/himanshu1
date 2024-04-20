# Use the official NGINX image as the base image
FROM nginx:latest

# Copy custom configuration file to NGINX config directory
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static files to NGINX web root directory
COPY static-html-directory /usr/share/nginx/html

# Expose port 80 to allow external access to the NGINX server
EXPOSE 80
