FROM centos:centos7
LABEL maintainer="SergeiTiT"
RUN yum update -y && yum install -y epel-release && yum install -y nginx  && yum clean all
# apache RUN echo "<h1>Sergei TiT httpd container</h1>"  > /var/www/html/index.html
RUN echo "<h1>---------======== Sergei TiT==========-------- </h1>"  > /usr/share/nginx/html/index.html
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
EXPOSE 80
CMD [ "/usr/sbin/nginx" ]