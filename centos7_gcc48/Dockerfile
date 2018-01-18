FROM centos:7
MAINTAINER wangxin "wangxin0072000@gmail.com"  
USER root
RUN yum -y install epel-release
RUN yum -y install gdb git automake patch logrotate libpng-devel libjpeg-devel man curl vim make gcc-c++-4.8.5 gcc-4.8.5 cmake wget tar bzip2 unzip dpkg vim-enhanced passwd boost-devel libzip libzip-devel zlib-devel libcurl-devel python-devel gflags-devel glog-devel lmdb-devel openblas-devel python-pip thrift thrift-devel gperftools-devel gperftools-libs atlas-devel protobuf-devel leveldb-devel snappy-devel opencv-devel hdf5-devel
RUN yum clean all
RUN pip install --upgrade pip