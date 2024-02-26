## Laravel and Composer Useful Commands

### Maintenance

#### Clear Application Cache
```bash
php artisan cache:clear
```

#### Clear Route Cache
```bash
php artisan route:clear
```

#### Clear Configuration Cache
```bash
php artisan config:clear
```

#### Clear Compiled Views
```bash
php artisan view:clear
```

#### Clear Compiled Classes
```bash
php artisan clear-compiled
```

#### Regenerate Class Loader
```bash
composer dump-autoload
```

### Database

#### Create a Migration
```bash
php artisan make:migration name_of_your_migration
```

#### Create a Table Migration
```bash
php artisan make:migration create_your_table_name_table --create=your_table_name
```

#### Add a Column to Existing Table Migration
```bash
php artisan make:migration add_some_column_to_your_table_name_table --table=your_table_name
```

### Debugging

#### List All Registered Routes
```bash
php artisan route:list
```

### Optimization

#### Optimize Application
```bash
php artisan optimize
```

#### Cache Configuration
```bash
php artisan config:cache
```

#### Cache Routes
```bash
php artisan route:cache
```

#### Cache Views
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
