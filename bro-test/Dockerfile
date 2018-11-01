FROM geerlingguy/docker-centos7-ansible:latest
LABEL maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

RUN yum install -y unzip libpcap gperfools-libs \
    libmaxminddb jemalloc git

CMD ["/usr/lib/systemd/systemd"]
