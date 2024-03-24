# Use NGINX Alpine version as the base image
FROM nginx:alpine

# Copy the static content into the container
COPY public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
 
