FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello world" > /usr/share/nginx/html/hello.html
CMD [ "nginx", "-g", "daemon off;" ]