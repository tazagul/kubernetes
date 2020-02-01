FROM ubuntu:latest
LABEL maitainer="Tazagul Kumarova"
RUN apt-get update -y && apt-get install apache2 -y
EXPOSE 80 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
