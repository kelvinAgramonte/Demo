# Use NGINX to serve static website
FROM nginx:alpine

# Remove the default nginx site
RUN rm -rf /usr/share/nginx/html/*

# Copy project files to the nginx folder
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80