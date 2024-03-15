# wordpress

version: 6.4.3

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
