FROM nginx

EXPOSE 8123

RUN mkdir /app
COPY ./app/ /app
#COPY ./nginx/nginx.conf /etc/nginx/
#COPY ./nginx/sites/default.conf /etc/nginx/sites-available/
COPY ./default.conf /etc/nginx/conf.d/


CMD ["/usr/sbin/nginx", "-g", "daemon off;"]


