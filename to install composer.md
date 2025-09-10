     sudo php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
     sudo php composer-setup.php
     sudo php -d memory_limit=-1 composer.phar require aws/aws-sdk-php
     sudo cp composer.phar /usr/local/bin/composer
     composer --version
