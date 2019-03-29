# Lutris-RHEL-CentOS7
Packages and method to install Lutris on RHEL and CentOS 7.x

# Important notes

Remove previous versions of lutris if installed 

sudo yum remove lutris

# Install Instructions

git clone https://github.com/jatin-cbs/Lutris-RHEL-CentOS7/tree/master

cd into the directory 

For Lutris version 4.21 (Tested)

sudo yum install lutris-0.4.21-1.el7.noarch.rpm

For Lutris version 4.23 (Tested)

sudo yum install lutris-0.4.23-1.el7.noarch.rpm

sudo ln -s /usr/lib/python3.6/site-packages/lutris /usr/lib/python3.4/site-packages/


no need to install vulkan and wine dependencies and included. 
