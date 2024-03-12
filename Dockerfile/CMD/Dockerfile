FROM almalinux:8
RUN yum update -y && \
    yum install nginx -y
#command to run nginx container in foreground
CMD ["nginx","-g","daemon off;"]    