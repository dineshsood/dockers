# dockers

sudo yum install -y yum-utils device-mapper-persistent-data lvm2
  
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
    
sudo yum install -y http://mirror.centos.org/centos/7/extras/x86_64/Packages/container-selinux-2.55-1.el7.noarch.rpm

sudo yum install docker-ce

sudo systemctl start docker

sudo docker run hello-world
