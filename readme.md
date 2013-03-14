# CodeIgniter CLI Migrations

## Installation

Clone the repo (or just ```migrate.php```) into your ```application/controllers``` directory.

Load up a shell (you already did that, right?) and change to your project's base dir. Migrate!*

## Usage

Migrate to latest version

```php index.php migrate```

Migrate to current version as defined in ```config/migrations.php```

```php index.php migrate "current"```

Migrate to a specific version

```php index.php migrate version "42"```

Rollback to the previous version

```php index.php migrate rollback```

Rollback to some other version

```php index.php migrate rollback "13"```

Rollback all the migrations

```php index.php migrate uninstall```


* * *

\* I'm assuming you actually have some migrations to run. If not, go read the [user_guide](http://ellislab.com/codeigniter/user_guide/).
