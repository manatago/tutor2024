FROM nginx:latest

RUN rm -f /etc/nginx/conf.d/*

ADD nginx.conf /etc/nginx/conf.d/nginx.conf

CMD /usr/sbin/nginx -g 'daemon off;'