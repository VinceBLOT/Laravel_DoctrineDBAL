Laravel_DoctrineDBAL
=======

Doctrine DBAL integration for Laravel

## Overview

`nayjest/laravel-doctrine-dbal` package provides:
* **Doctrine DBAL connection** based on your default Laravel DB connection, initialized by same PDO connection object
* **Facade** for default Doctrine DBAL connection
* **SQL queries logging setup**. Queries executed via Doctrine DBAL will be present in DB::getQueryLog() and "Queries" tab of `barryvdh/laravel-debugbar`

## Installation

Via [Composer](https://getcomposer.org)

* Run following command:
```bash
composer require nayjest/laravel-doctrine-dbal
```
* Register Nayjest\LaravelDoctrineDBAL\ServiceProvider in your application configuration file

* Add facade alias:

```php
    'DBAL' => 'Nayjest\LaravelDoctrineDBAL\Facade',
```

## Testing

Run following command:

```bash
phpunit
```

## License

© 2014 — 2015 Vitalii Stepanenko

Licensed under the MIT License.

Please see [License File](LICENSE) for more information.
