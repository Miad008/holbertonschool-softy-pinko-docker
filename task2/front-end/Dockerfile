# Use the latest nginx image
FROM nginx:latest

# Copy static files to the web root
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy custom Nginx config
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
