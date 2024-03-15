# wordpress

**version:** 6.4.3

Only store original wordpress resources from 'wordpress home page'. Other resources are not included

You can set up apache php or openlitespeed to make a web server: 

- Instructions for setup wordpress on Ubuntu Apache2: [Link]([https://vietnix.vn/cai-wordpress-tren-ubuntu/?gad_source=1&gclid=Cj0KCQjwwMqvBhCtARIsAIXsZpZL00picWPXmhibWgzy5s8DOw02AixlvZtoIVAJMH4KK2Ef4rYR6lkaAqB4EALw_wcB])
- Instructions for setup wordpress on Ubuntu OpenLiteSpeed: [Link](https://thuanbui.me/wordpress-mariadb-openlitespeed-phpmyadmin-docker-compose/)
  - Github repo [OpenLiteSpeed](https://github.com/litespeedtech/ols-docker-env)

===

git clone code to your OS.

```
git clone git@github.com:anhit-workspace/wordpress.git
```

or download from home page wordpress


```plain
wget https://wordpress.org/latest.tar.gz
```


unzip and move to your workspace


```plain
tar xvafwordpress-6.4.3.tar.gz
```

move to wordpress folder


```plain
sudo mv wordpress
```

change permision wordprss folder

```plain
sudo chown -R www-data:www-data /var/www/wordpress/
sudo chmod -R 755 /var/www/wordpress/
```

===

- Tìm các template free của wordpress với từ khoá: nulled
