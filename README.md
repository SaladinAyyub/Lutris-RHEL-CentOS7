# Lutris-RHEL-CentOS7
Packages and method to install Lutris on RHEL and CentOS 7.x

git clone https://github.com/jatin-cbs/Lutris-RHEL-CentOS7/tree/master

cd into the directory 

For Lutris version 4.21 (Tested)

sudo yum install lutris-0.4.21-1.el7.noarch.rpm

For Lutris version 4.23 (Tested)

sudo yum install lutris-0.4.23-1.el7.noarch.rpm

For Lutris 5.0 (not working currently due to https://github.com/jatin-cbs/Lutris-RHEL-CentOS7/issues/1)


no need to install vulkan and wine dependencies and included.

if you expirience module not found error please do 

sudo mv /usr/lib/python3.6/site-packages/lutris /usr/lib/python3.4/site-packages/
