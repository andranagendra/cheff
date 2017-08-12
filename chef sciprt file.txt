
cd /opt/

mkdir chef

cd chef
  
wget  https://packages.chef.io/files/stable/chefdk/1.5.0/el/6/chefdk-1.5.0-1.el6.x86_64.rpm

rpm -ivh  chefdk-1.5.0-1.el6.x86_64.rpm

chef -v

knife -v

