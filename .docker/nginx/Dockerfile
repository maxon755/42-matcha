FROM nginx

COPY ./config/default.conf /etc/nginx/conf.d/

WORKDIR /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
