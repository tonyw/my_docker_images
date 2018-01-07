FROM ubuntu:16.04
  
MAINTAINER wangxin "wangxin0072000@gmail.com"  

USER root

RUN apt-get -y update 
RUN apt-get -y upgrade 
RUN apt-get -y dist-upgrade
RUN apt-get -y install cmake libssl-dev libsodium-dev libpcre3-dev libleveldb-dev libboost-all-dev libgmp-dev libprotobuf-dev protobuf-compiler libjansson-dev screen build-essential pkg-config libc6-dev m4 g++-multilib autoconf libtool ncurses-dev unzip git python zlib1g-dev wget bsdmainutils automake
RUN apt-get -y install npm
RUN mkdir /zmaster
WORKDIR /zmaster
RUN npm install n -g
RUN n stable
RUN git clone https://github.com/joshuayabut/node-open-mining-portal.git z-nomp
WORKDIR /zmaster/z-nomp
RUN npm update
RUN npm install