Here are the commands that we’ll run to build and install Python 3 RedHat based systems:
```
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
[root@vaio DevOps]# wget http://python.org/ftp/python/3.6.8/Python-3.6.8.tar.xz
[root@vaio DevOps]# tar xf Python-3.7.3.tar.xz
[root@vaio DevOps]# cd Python-3.7.3
[root@vaio DevOps]# ./configure --enable-optimizations
[root@vaio DevOps]# make altinstall
[root@vaio DevOps]# exit
```
> Important: make altinstall causes it to not replace the built in python executable.



Here are the commands that we’ll run to build and install Python 3 Debian based systems:
```
[que@vaio DevOps]$ su -
[root@vaio DevOps]# apt-get install -y \
  wget \
  build-essential \
  libssl-dev \
  zlib1g-dev \
  libbz2-dev \
  libreadline-dev \
  libsqlite3-dev \
  libncurses5-dev \
  libncursesw5-dev \
  xz-utils \
  tk-dev

[root@vaio DevOps]# cd /usr/src
[root@vaio DevOps]# wget http://python.org/ftp/python/3.6.8/Python-3.6.8.tar.xz
[root@vaio DevOps]# tar xf Python-3.6.8.tar.xz
[root@vaio DevOps]# cd Python-3.6.8
[root@vaio DevOps]# ./configure --enable-optimizations
[root@vaio DevOps]# make altinstall
[root@vaio DevOps]# exit

Note: make altinstall causes it to not replace the built in python executable.
```
Upgrade Pip (Don't ask questions - just follow the instructions)
[root@vaio DevOps]$ sudo pip3.6 install --upgrade pip

> The version of pip that we have might be up-to-date, but it’s good practice to try to update it after the installation. We need to use the pip3.6 executable because we’re working with Python 3, and we use sudo so that we can write files under the /usr/local directory.
