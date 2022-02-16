# Laravel

You need to following these steps.

- Install Xampp
- Install Composer
- Install Laravel 9

## Xampp

First you need to install the [xampp](https://www.apachefriends.org/index.html). 

In xampp start the Apache and Mysql service.

Now you can see the [PHP info](http://localhost/dashboard/phpinfo.php).

or check php version by using this command :
```
php -v
```

## Composer
> A Dependency Manager for PHP
### What is composer?
Composer is a dependency manager for PHP and with the help of the composer we don't need to install the dependencies manually. Every dependency is installed by the composer automatically in the **vendor folder**.

Download Composer by this [Site](https://getcomposer.org/download/). Install the composer.

Check composer version :
```
composer
```


## Install laravel?

You may install the Laravel Installer as a global Composer dependency. You can run this command only one time.
```
composer global require laravel/installer
```

Check laravel version :
```
laravel
```

Now go to your working directory.

```
cd Users\username
cd documents\GitHub
cd repository_name
```

Everytime you need to add a project on **Laravel**.
Run this command :
```
laravel new project_name

cd project_name
 
php artisan serve
```


> First find the solution :hourglass_flowing_sand: to the problem then write the code :fire:. (Ali Raza)




