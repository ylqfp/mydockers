# machine learing development environment, mainly fast OTHER than stable
FROM ubuntu:15.10
MAINTAINER Fischer Yu <ylqfp@qq.com>
ADD sources.list.1510 /etc/apt/source.list
ADD vimrc /root/.vimrc
RUN apt-get update
RUN apt-get install -y vim build-essential gfortran git wget curl subversion docker.io
RUN apt-get install -y libopenblas-dev 
RUN apt-get install -y python-dev python-pip libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libboost-all-dev libhdf5-serial-dev libgflags-dev libgoogle-glog-dev liblmdb-dev protobuf-compiler python-nose python-numpy python-scipy libarmadillo-dev
CMD ["/bin/bash"]