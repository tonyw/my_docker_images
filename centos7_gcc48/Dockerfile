FROM registry.cn-hangzhou.aliyuncs.com/carfield-centos/centos7:7
  
MAINTAINER wangxin "wangxin0072000@gmail.com"  
  
  
# Install curl,gcc,cmake
RUN yum update -y
RUN yum -y install curl
RUN yum -y install gcc-c++-4.8.5-16.el7
RUN yum -y install cmake
RUN yum -y install gcc-4.8.5-16.el7
USER root
RUN yum -y remove supervisor.noarch 3.1.4-1.el7
RUN yum -y remove nodejs-supervisor.noarch 0.6.0-2.el7

  
