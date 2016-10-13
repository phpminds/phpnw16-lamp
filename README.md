# PHP 7 LAMP Stack 

An Ubuntu 16.04 LAMP stack with PHP 7 for the PHPSchoo.io Workshop at PHPMiNDS

**Note** It uses ansible but it is loaded through the VM so it is Windows-friendly.


### Server Setup

* **Server names**: `phpschool.local` and `www.phpschool.local` 
* **IP**: `192.168.22.123`
* **Document Root**: `/var/www/public`
* **DB Credentials**: `root` / `Admin123` and `web_user` / `User123`


**Note* Document root can be changed in `server/ansible/vars/common.yml`

### Adding sites

To make it simple for these tutorials, just add the packages provided within the `application/public` directory and copy the `.htaccess` file as and where needed.