FROM geerlingguy/docker-centos7-ansible:latest
LABEL maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

RUN yum install -y unzip libpcap gperftools-libs \
    libmaxminddb jemalloc git

RUN pip install --upgrade pip setuptools

CMD ["/usr/lib/systemd/systemd"]
