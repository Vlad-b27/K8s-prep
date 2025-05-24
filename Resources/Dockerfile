# Use official nginx image
FROM nginx:latest

# Remove the default nginx page
RUN rm -rf /usr/share/nginx/html/*

# Copy custom HTML into the nginx html directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80
