FROM        centos:7
RUN         yum install httpd -y
CMD         ["httpd","-DFOREGROUND"]
HEALTHCHECK --interval=5s --timeout=3s \
  CMD curl -f http://localhost/ || exit 1