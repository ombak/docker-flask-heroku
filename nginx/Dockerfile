FROM nginx

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/

RUN rm /etc/nginx/conf.d/default.conf
COPY ujicoba04.conf /etc/nginx/conf.d/
