FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello world from layer 2" > /usr/share/nginx/html/hello.html
RUN echo "Hi world from layer2 " > /usr/share/nginx/html/hi.html
RUN yum install git -y \
    && yum install maven -y
CMD [ "nginx", "-g", "daemon off;" ]