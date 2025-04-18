FROM nginx:1.27.5-alpine


COPY fabulove.conf /etc/nginx/conf.d
COPY cert/* /etc/nginx/ssl/

CMD ["nginx", "-g", "daemon off;"]