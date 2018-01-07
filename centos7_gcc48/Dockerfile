FROM centos:7
  
MAINTAINER wangxin "wangxin0072000@gmail.com"  

USER root

RUN yum update -y

RUN yum -y install curl
RUN yum -y install gcc-c++-4.8.5
RUN yum -y install gcc-4.8.5
RUN yum -y install cmake
RUN yum -y install make
RUN yum -y install vim
RUN yum -y install boost-devel
RUN yum -y install man
RUN yum -y install libzip
RUN yum -y install libzip-devel
RUN yum -y install zlib-devel
RUN yum -y install libcurl-devel
RUN yum -y install python-devel
RUN yum -y install epel-release
RUN yum -y install python-pip
RUN yum -y install git automake patch logrotate libpng-devel libjpeg-devel
RUN yum -y install wget tar bzip2 unzip dpkg vim-enhanced passwd
RUN yum -y install gdb
RUN yum clean all

RUN pip install --upgrade pip