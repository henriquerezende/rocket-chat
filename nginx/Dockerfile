FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY ./sites/nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80 443
