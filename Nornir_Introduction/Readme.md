For: scrapli.exceptions.ScrapliAuthenticationFailed: Host key verification failed

 cat  ~/.ssh/config
 Host * KexAlgorithms diffie-hellman-group1-sha1
 
 
 Install and configure python:
 ==============================
  wget https://www.python.org/ftp/python/3.9.13/Python-3.9.13.tgz
 ls
 gunzip Python-3.9.13.tgz
 ls
 tar -xvf Python-3.9.13.tar
 ls
 cd Python-3.9.13/
 ls
 ./configure --enable-optimizations
 sudo yum install gcc openssl-devel bzip2-devel libffi-devel zlib-devel
 ./configure --enable-optimizations
 sudo make altinstall
 python3.9 --version
 sudo yum install python-pip
 pip -version
 pip -v
 pip --version
 sudo yum install epel-release
 sudo yum install python-pip3
