FROM almalinux:8
RUN yum update -y && \
    yum install nginx -y
#command to run nginx container in foreground
RUN rm -rf /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
COPY Ayaan /usr/share/nginx/html