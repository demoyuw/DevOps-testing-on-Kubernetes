FROM nginx:1.16.0-alpine
COPY ./reactjs/build /usr/share/nginx/html
# COPY ./default.conf /etc/nginx/conf.d
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]