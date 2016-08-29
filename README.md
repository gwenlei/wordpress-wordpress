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
#wp_cli_url: https://raw.github.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
wp_db_host: localhost
wp_db_import: false
wp_debug: false
wp_delete_content: false
wp_lang: en_US
wp_table_prefix: wp_
wp_version: 4.4.2
wp_root: /var/www/html/wordpress
wp_db_name: example_com
wp_db_user: example_user
wp_db_password: password
wp_admin_password: password
wp_admin_email: admin@example.dev
host: localhost
env: development
site_name: example.com

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
