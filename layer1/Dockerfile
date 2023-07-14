# keep the static instructions at top, keep frequently changed instructions at below
FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello world" > /usr/share/nginx/html/hello.html
RUN echo "Hi world" > /usr/share/nginx/html/hi.html
RUN yum install git -y
RUN yum install maven -y
CMD [ "nginx", "-g", "daemon off;" ]