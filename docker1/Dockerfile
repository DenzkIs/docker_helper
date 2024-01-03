FROM ubuntu:22.04
LABEL author=Den
RUN apt-get update
RUN apt-get install nginx -y
COPY files/index.html /var/www/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]