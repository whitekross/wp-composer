1 - Install dependencies with composer: 

    composer install

2 - Add your site information to wp-cli.yml and run config
    
    ./vendor/bin/wp core config

3 - Run installer with wp-cli

    ./vendor/bin/wp core install
    
4 - Update Wordpress option and activate the installed theme

    ./vendor/bin/wp theme activate hueman

5 - Update plugins (optional)
    
    ./vendor/bin/wp plugin activate json-rest-api wp-badge-poser akismet 

6 - Launch built-in server (for development)

    ./vendor/bin/wp server --host=<host>

