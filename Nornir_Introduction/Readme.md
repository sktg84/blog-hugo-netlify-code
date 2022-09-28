Install and configure python:
 ============================

     wget https://www.python.org/ftp/python/3.9.13/Python-3.9.13.tgz
     
     gunzip Python-3.9.13.tgz
     
     tar -xvf Python-3.9.13.tar
     
     cd Python-3.9.13/
     
     ./configure --enable-optimizations
     sudo yum install gcc openssl-devel bzip2-devel libffi-devel zlib-devel
     ./configure --enable-optimizations
     sudo make altinstall
     python3.9 --version
     sudo yum install python-pip
    
     sudo yum install epel-release
     sudo yum install python-pip3
  


 - **For: scrapli.exceptions.ScrapliAuthenticationFailed: Host key
   verification failed**



 cat  ~/.ssh/config
 Host * KexAlgorithms diffie-hellman-group1-sha1
