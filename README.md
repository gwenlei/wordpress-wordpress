Role Name
=========
gwenlei.wordpress-wordpress

Requirements
------------
ubuntu16.04 xenial

Role Variables
--------------
defaults/main.yml

wp_admin_user: admin
wp_cli_bin: /usr/bin/wp
wp_cli_url: http://192.168.0.82/downloads/wp-cli.phar
wp_lang: en_US
wp_version: 4.6 
wp_root: /var/www/html/wordpress
#wp_cli_url: https://raw.github.com/wp-cli/builds/gh-pages/phar/wp-cli.phar

Dependencies
------------
none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gwenlei.wordpress-wordpress }

License
-------
MIT

Author Information
------------------
onecloud
