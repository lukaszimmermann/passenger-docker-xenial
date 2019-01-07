FROM phusion/baseimage:0.10.1
LABEL maintainer="luk.zim91@gmail.com"

ADD . /pd_build
RUN /pd_build/install.sh
CMD ["/sbin/my_init"]
EXPOSE 80 443
