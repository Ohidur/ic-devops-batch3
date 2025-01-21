# Base Image for Nginx
FROM nginx:alpine

# Set the working directory
WORKDIR /app

# Copy the web files
COPY /web/ /usr/share/nginx/html

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]