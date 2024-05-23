# BookStack

### pre-requisite:

PHP >= 8.0.2
MySQL >= 5.7 or MariaDB >= 10.2
Git Version Control
Composer >= v2.0 <!-- https://getcomposer.org/ -->
A PHP Compatible Webserver apache2

## Installation steps:
 [Refer here for installation Methods](https://www.bookstackapp.com/docs/admin/installation/)

* I am using ubuntu 22.04 (script)

# Download the script
wget https://raw.githubusercontent.com/BookStackApp/devops/main/scripts/installation-ubuntu-22.04.sh

# Make it executable
chmod a+x installation-ubuntu-22.04.sh

# Run the script with admin permissions
sudo ./installation-ubuntu-22.04.sh

After Execution:

----------------------------------------------------------------
Setup finished, your BookStack instance should now be installed!
- Default login email: admin@admin.com
- Default login password: password
- Access URL: http://172.16.4.248/ or http://172.16.4.248/
- BookStack install path: /var/www/bookstack
- Install script log: /root/bookstack_install_1704366784.log
---------------------------------------------------------------

Now you can login with the abive url `http://172.16.4.248/`


