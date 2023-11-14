FROM alpine:3.14
LABEL name="myim"
RUN apk add nginx
COPY nginx.conf /etc/nginx/nginx.conf 
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 8080
CMD ["nginx"]