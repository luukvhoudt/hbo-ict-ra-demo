FROM nginx:mainline-alpine

# Configure NGINX to serve our app
COPY ./nginx_default.conf /etc/nginx/conf.d/default.conf

# Distribute our app
COPY ./app /usr/local/src