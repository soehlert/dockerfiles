FROM centos:7
LABEL maintainer="Sam Oehlert <sam.oehlert@gmail.com>"

RUN yum -y install epel-release ruby-devel gcc make rpm-build rubygems
RUN yum -y install jq cargo openssl-devel PyYAML lz4-devel gcc libpcap-devel \
    pcre-devel libyaml-devel file-devel zlib-devel jansson-devel nss-devel \
    libcap-ng-devel libnet-devel tar make libnetfilter_queue-devel lua-devel \
RUN gem install fpm

