## Laravel and Composer Useful Commands


### Make

```
php artisan make:<type> <name>
```

**Types**:
  * make:cast  
  * make:channel  
  * make:command  
  * make:component  
  * make:controller  
  * make:event  
  * make:exception  
  * make:factory  
  * make:job  
  * make:listener  
  * make:mail  
  * make:middleware  
  * make:migration  
  * make:model  
  * make:notification  
  * make:observer  
  * make:policy  
  * make:provider  
  * make:request  
  * make:resource  
  * make:rule  
  * make:scope  
  * make:seeder  
  * make:test  
  * make:view  
### Domain

#### Controllers
```
php artisan make:controller API/PhotoController --model=Photo --api
```
* `--api`
* `--resource`
* `--model ModelName`
* `--parent`
nested resources
* `--invokable`
use case
```
php artisan make:request StorePostRequest

php artisan make:service ApiResponseService
```

#### Magic Methods
```
composer require barryvdh/laravel-ide-helper

php artisan ide-helper:generate

php artisan ide-helper:models
```


### Database

#### Migration

```bash
php artisan migrate
```

```bash
php artisan make:migration name_of_your_migration
```

**Options**:
* `--create=your_table_name`
* `--table=your_table_name`

### Maintenance

```bash
php artisan cache:clear

php artisan route:clear

php artisan config:clear

php artisan view:clear

php artisan clear-compiled
composer dump-autoload
```


### Debugging

#### List All Registered Routes
```bash
php artisan route:list
```

### Optimization

```bash
php artisan optimize
```

```bash
php artisan config:cache
```

```bash
php artisan route:cache
```

```bash
php artisan view:cache
```

### Testing

#### Run PHPUnit Tests
```bash
php artisan test
```

### Composer

#### Update All Dependencies
```bash
composer update
```

#### Install Specific Package
```bash
composer require package/name
```

### Miscellaneous

#### Serve Application
```bash
php artisan serve
```

#### Generate Application Key
```bash
php artisan key:generate
```


This markdown file provides a collection of commonly used Laravel Artisan and Composer commands that can be useful for various tasks, including maintenance, database migrations, debugging, optimization, and testing.
