FROM        centos:7
RUN         yum install httpd -y
CMD         ["httpd","-DFOREGROUND"]
HEALTHCHECK --interval=5s --timeout=3s \
  CMD curl -f http://localhost/ || exit 1




#docker exec -it CONTID bash
#cd /var/www
#rm -rf html
# it will show as unhealthy