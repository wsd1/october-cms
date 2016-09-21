
# OctoberCMS 免官方安装版
====

官方安装依赖能够翻墙的环境，失败多了比较恶心，本repo解决此问题。只要github健在，一个clone 解决安装烦恼。


## 官方安装方法：

base install:

	mkdir oc
	cd oc
	curl -s https://octobercms.com/api/installer | php

    sudo chown -R dy:www-data ../oc
    sudo chmod -R g+wrx ../oc


setup:

	php artisan october:install

	# for sqlite db file access
    sudo chown -R dy:www-data ../oc
    sudo chmod -R g+wrx ../oc


## 本repo安装方法

找个好风水的路径，比如 ~\product\

	git clone https://github.com/wsd1/october-cms.git
	mv october-cms oc
	cd oc

    sudo chown -R dy:www-data ../oc
    sudo chmod -R g+wrx ../oc

	# If you chose sqlite, this step will generate sqlite db file.
	php artisan october:install

	# for sqlite db file access
    sudo chown -R dy:www-data ../oc
    sudo chmod -R g+wrx ../oc

安装之后，请立即安装 builder和user插件，详情自觅。

20160921.


