# NaUeb

First, you will need to install `composer` in your machine. It is a package manager for PHP.

In the first pull, execute in the laravel's root directory:
```
composer install
```

At every commit, do the following:

If there is a change in the `composer.json` file, go to the laravel's folder and execute:
```
composer dump-autoad;
composer update;
```

To check the site, it is required to start the httpd daemon and to listen the Laravel project on a port.
To listen Laravel on the 8888 port, do the following:
```
cd <NaUeb_root_dir>
php -S localhost:8888 -t site/public
firefox localhost:8888
```
