openstack
=========

openstack instalation

    sudo yum install -y http://rdo.fedorapeople.org/rdo-release.rpm
    sudo yum install -y openstack-packstack
    packstack --answer-file=

## install mysql community

    wget http://dev.mysql.com/get/mysql-community-release-el6-5.noarch.rpm
    sudo yum localinstall mysql-community-release-el6-*.noarch.rpm
    sudo service mysqld start
    sudo chkconfig mysqld on
    chkconfig --list mysqld
    sudo yum install mysql-community-server
    sudo service mysqld start
    sudo chkconfig mysqld on
    chkconfig --list mysqld
    mysql_secure_installation
    service mysqld restart
