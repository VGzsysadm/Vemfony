# Vemfony {WorkInProgress}
<center>Frontend for Veeam Backup Enterprise Manager</center>

### Prerequisites

* PHP 7.1 or higher
* Mysql
* Composer

## Getting Started

Clone the project

```
https://github.com/VGzsysadm/Vemfony.git
```
### Installing

Install dependencies

```
cd Vemfony
composer install
```
### Prod mode

Create ENV variables in the host, confirm data at doctrine.yaml

Create the database and tables:

```
php bin/console doctrine:database:create
php bin/console make:migration
php bin/console doctrine:migrations:migrate
```

## Built With

* [Symfony 4](https://symfony.com/doc/current/index.html)

## Authors

* **VGzsysadm** - *https://sysadm.es* - [@VGzsysadm](https://github.com/VGzsysadm)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/VGzsysadm/Vemfony/blob/master/LICENSE.MD) file for details


