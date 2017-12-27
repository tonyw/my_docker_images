FROM registry.cn-hangzhou.aliyuncs.com/carfield-centos/centos7:7
  
MAINTAINER wangxin "wangxin0072000@gmail.com"  
  
  
# Install curl,gcc,cmake
RUN yum update -y
RUN yum -y install curl
RUN yum -y install gcc-c++-4.8.5-16.el7
RUN yum -y install cmake
RUN yum -y install gcc-4.8.5-16.el7
RUN gcc --version
RUN g++ --version
RUN uname -a
USER root
RUN mkdir -p /var/log/supervisor
COPY supervisord.conf /etc/supervisor.conf.d/supervisord.conf
  
