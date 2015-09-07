# machine learing development environment, mainly fast OTHER than stable
FROM ubuntu:14.04
MAINTAINER Fischer Yu <ylqfp@qq.com>
ADD sources.list.1404 /etc/apt/sources.list
ADD vimrc /root/.vimrc
RUN apt-get update
RUN apt-get install -y vim build-essential gfortran git wget curl subversion cmake zip unzip htop dstat
RUN apt-get install -y libopenblas-dev python-dev python-pip python-nose python-numpy python-scipy
RUN apt-get install -y libprotobuf-dev libleveldb-dev libsnappy-dev  libhdf5-serial-dev libgflags-dev libgoogle-glog-dev liblmdb-dev protobuf-compiler  libsuperlu-dev 
RUN apt-get install -y libopencv-dev libboost-all-dev
RUN apt-get install -y libarmadillo-dev
CMD ["/bin/bash"]