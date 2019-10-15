FROM geerlingguy/docker-centos7-ansible:latest
LABEL maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

ARG PYTHON_VERSION=python36
ARG GECKODRIVER_VERSION=0.24.0
ARG DJANGO_LOG_LEVEL=INFO

RUN yum install -y ${PYTHON_VERSION}-devel ${PYTHON_VERSION}-pip firefox scl-utils; \
    yum install -y http://www6.atomicorp.com/channels/atomic/centos/7/x86_64/RPMS/atomic-heimdal-runtime-7.5.0-8.el7.x86_64.rpm \
      http://www6.atomicorp.com/channels/atomic/centos/7/x86_64/RPMS/atomic-sqlite-3.8.5-6803.el7.art.x86_64.rpm
RUN cp /opt/atomicorp/atomic/root/usr/

RUN yum install -y unzip libpcap gperftools-libs \
    libmaxminddb jemalloc git

CMD ["/usr/lib/systemd/systemd"]
