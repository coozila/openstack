openstack
=========

openstack instalation




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
