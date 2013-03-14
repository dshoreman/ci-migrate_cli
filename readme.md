# CodeIgniter CLI Migrations

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
