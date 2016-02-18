# PHP Development System

This Vagrant System provides the following Software:

- Ubuntu Trusty 64Bit
- PHP 5.6
- MySQL 5.5
- Apache 2
- Composer
- PHPMyAdmin

Additional Information:

- The current folder is mounted to `/var/www/html` inside the Guest System.
- The IP Address of the Guest is 192.168.56.101
    - A Entry to `/etc/hosts` should be added on the Host System
- PHPMyAdmin is Available on Port 81
- Database credentials can be Changed in `system/bootstrap.sh`

When a grey Box is displayed during a `vagrant up --provision`, just destroy the box and start it again.
