FROM nginx
COPY index.html /usr/share/nginx/html

COPY ../nginx.conf /etc/nginx/conf.d/
COPY /etc/letsencrypt/live/angel.popovdesigns.uk/fullchain.pem /etc/nginx/ssl/fullchain.pem
COPY /etc/letsencrypt/live/angel.popovdesigns.uk/privkey.pem /etc/nginx/ssl/privkey.pem