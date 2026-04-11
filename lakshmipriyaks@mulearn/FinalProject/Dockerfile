FROM nginx:alpine

# Remove default nginx webpage
RUN rm -rf /usr/share/nginx/html/*

# Copy our webpage
COPY index.html /usr/share/nginx/html/

# Expose port
EXPOSE 80