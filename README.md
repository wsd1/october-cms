
# October cms
====

base install:

	mkdir otc
	cd otc
	curl -s https://octobercms.com/api/installer | php

    sudo chown -R dy:www-data ../oct

    sudo chmod -R g+wrx ../oct


setup:

	php artisan october:install