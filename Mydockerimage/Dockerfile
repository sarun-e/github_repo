# Use a minimal base image
FROM nginx:alpine

# Create a directory for your web content
RUN mkdir -p /usr/share/nginx/html

# Copy your HTML file to the web content directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 for Nginx
EXPOSE 80

