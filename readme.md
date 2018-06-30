# Laravel 5 with MongoDB #

Sample Laravel project with mongodb support 

## Installation ##

* `git clone git@github.com:jayant1993/Sample-laravel-mongodb-project.git projectname`
* `cd projectname`
* `composer install`
* `php artisan key:generate`
* Create .env file from .env.example
* Create a database and inform *.env*
* `php artisan serve` to start the app on http://localhost:8000/

Another way to install it is to download and upload [this package](https://github.com/jayant1993/Sample-laravel-mongodb-project/archive/master.zip), unpack it in your server folder, and just launch it and follow the above installation process.

## Usage ##

#### Create Model ####

```
use Moloquent\Eloquent\Model as Eloquent;
class User extends Eloquent {}
```

follow other instructions from <a href="https://moloquent.github.io/master/basic/">moloquent website</a>


## Packages included ##

* moloquent/moloquent


