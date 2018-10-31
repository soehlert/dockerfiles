FROM geerlingguy:docker-os7-ansible
LABEL maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

RUN yum install -y unzip libpcap gperfools-lib \
    libmaxminddb jemalloc git 

CMD ["/usr/lib/systemd/systemd"]
