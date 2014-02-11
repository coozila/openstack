openstack
=========

openstack instalation

    sudo yum install -y http://rdo.fedorapeople.org/rdo-release.rpm
    sudo yum install -y openstack-packstack
    packstack --answer-file=

## install mysql community

    sudo yum localinstall mysql-community-release
    sudo service mysqld start
    sudo chkconfig mysqld on
    chkconfig --list mysqld
    sudo yum install mysql-community-server
    sudo service mysqld start
    sudo chkconfig mysqld on
    chkconfig --list mysqld
    mysql_secure_installation
    service mysqld restart
