#base OS
FROM almalinux:8
#installing or updating required packages
RUN yum update -y && \
    yum install nginx -y
#command to run nginx container in foreground
RUN rm -rf /usr/share/nginx/html/index.html
#we are starting server
CMD ["nginx","-g","daemon off;"]
#we are copying app code
COPY Ayaan /usr/share/nginx/html