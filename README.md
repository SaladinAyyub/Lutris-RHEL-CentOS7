# Lutris-RHEL-CentOS7
Packages and method to install Lutris on RHEL and CentOS 7.x

git clone https://github.com/jatin-cbs/Lutris-RHEL-CentOS7

cd into the directory 

For Lutris version 4.21 (I tested on my machine)

sudo yum install lutris-0.4.21-1.el7.noarch.rpm

For Lutris version 4.23 (I didn't test on my machine)

sudo yum install lutris-0.4.23-1.el7.noarch.rpm

For Lutris 5.0

sudo yum install lutris-0.5.0.1-2.el7.x86_64.rpm

no need to install vulkan and wine dependencies and included.

if you expirience module not found error please do 

sudo mv /usr/lib/python3.6/site-packages/lutris /usr/lib/python3.4/site-packages/

sudo mv /usr/lib/python3.7/site-packages/lutris /usr/lib/python3.4/site-packages/


For Discussion please comment on 
https://github.com/lutris/lutris/issues/1364
