FROM nginx
RUN sed -i.bak 's/listen       80;/listen       8000;/' /etc/nginx/conf.d/default.conf; service nginx start
CMD ["nginx", "-g", "daemon off;"]
