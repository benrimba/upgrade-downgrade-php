# Upgrade atau Downgrade PHP di linux Ubuntu

sudo add-apt-repository ppa:ondrej/php

sudo apt-get update


sudo apt-get install php7.3

sudo apt-get install php7.3-cli php7.3-common php7.3-json php7.3-opcache php7.3-mysql php7.3-mbstring php7.3-zip php7.3-fpm php7.3-intl php7.3-simplexml


sudo a2dismod php7.4

sudo a2enmod php7.3

sudo service apache2 restart
