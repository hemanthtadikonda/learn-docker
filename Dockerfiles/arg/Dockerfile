FROM        centos:8
ARG         ENV
RUN         mkdir /${ENV}
ARG         APP_VERSION
ENV         APP_VERSION=${APP_VERSION}





#docker build --build-arg ENV=DEV --build-arg APP_VERSION=10.0.1 -t arg .
#you should provide build args
#docker run -it arg env