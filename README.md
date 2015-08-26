1 - Install with composer: 

    composer install

2 - Copy wp-config-sample.php to wp-config.php 

    cp wp-config-sample.php wp-config.php

and add your database information.

3  - Edit "url" in wp-cli file

    url: <host>

4 - Run install with cli 

    ./vendor/bin/wp core install --url=http://<host> --title="<title>" --admin_user=<user> --admin_password=<password> --admin_email=<email>
    
5 - Update Wordpress option and activete the installed theme

    ./vendor/bin/wp option set siteurl 'http://<host>/wp'
    ./vendor/bin/wp theme activate 'hueman'

6 - Launch built-in server

    ./vendor/bin/wp server --host=<host>

