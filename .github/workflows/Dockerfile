# Step 1: Use the official NGINX base image
FROM nginx:latest

# Step 2: Copy custom NGINX configuration file (optional)
# COPY ./my-nginx.conf /etc/nginx/nginx.conf

# Step 3: Copy website content or static files into the default directory served by NGINX
COPY ./html /usr/share/nginx/html

# Step 4: Expose port 80 (default HTTP port for NGINX)
EXPOSE 80

# Step 5: Start NGINX when the container launches
CMD ["nginx", "-g", "daemon off;"]
