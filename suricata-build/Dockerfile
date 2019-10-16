FROM centos:7
LABEL maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

RUN yum -y install epel-release ruby-devel gcc make rpm-build \
    rubygems wget

RUN yum -y install GeoIP-devel PyYAML cargo elfutils-libelf-devel file-devel \
    hiredis-devel jansson-devel jq libcap-ng-devel libnet-devel libnetfilter_queue-devel \
    libpcap-devel libyaml-devel lua-devel luajit-devel lz4-devel nss-devel openssl-devel \
    pcre-devel tar xz-devel zlib-devel

RUN gem install fpm

