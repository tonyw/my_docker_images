FROM centos:7
MAINTAINER wangxin "wangxin0072000@gmail.com"  
USER root
RUN yum -y install epel-release
RUN yum -y install gdb git automake patch logrotate libpng-devel libjpeg-devel man curl vim make gcc-c++-4.8.5 gcc-4.8.5 cmake wget tar bzip2 unzip dpkg vim-enhanced passwd boost-devel libzip libzip-devel zlib-devel libcurl-devel python-devel gflags-devel glog-devel lmdb-devel openblas-devel python-pip thrift thrift-devel gperftools-devel gperftools-libs atlas-devel protobuf-devel leveldb-devel snappy-devel opencv-devel hdf5-devel gnutls-devel cryptopp-devel lz4-devel yaml-cpp-devel hwloc-devel libxml2-devel
RUN yum clean all
RUN pip install --upgrade pip
RUN echo "Asia/shanghai" > /etc/timezone
RUN yum -y install java-1.7.0-openjdk*
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN yum -y install net-tools