Here are the commands that we’ll run to build and install Python 3:
[que@vaio DevOps]$ su -
[root@vaio DevOps]# yum groupinstall -y "development tools"
[root@vaio DevOps]# yum install -y \
  libffi-devel \
  zlib-devel \
  bzip2-devel \
  openssl-devel \
  ncurses-devel \
  sqlite-devel \
  readline-devel \
  tk-devel \
  gdbm-devel \
  db4-devel \
  libpcap-devel \
  xz-devel \
  expat-devel

[root@vaio DevOps]# cd /usr/src
[root@vaio DevOps]# wget http://python.org/ftp/python/3.6.4/Python-3.6.4.tar.xz
[root@vaio DevOps]# tar xf Python-3.6.4.tar.xz
[root@vaio DevOps]# cd Python-3.6.4
[root@vaio DevOps]# ./configure --enable-optimizations
[root@vaio DevOps]# make altinstall
[root@vaio DevOps]# exit

Important: make altinstall causes it to not replace the built in python executable.

