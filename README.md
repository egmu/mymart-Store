
<img src="https://mymartenterprises.com/wp-content/uploads/2020/02/mymart-red-logo-copy.png" alt="vfbot-wa" width="300" />
    <h1 align="center">Yii 2 Advanced Project Mymart</h1>
    <br>
</p>

# Instalasi
## 💻 Clone Repo & Make Advanced
```bash
> git clone https://github.com/egmu/mymart1.git
> cd mymart1
> php init
```

# Change DataBase
Change file main-local.php
```php
'db' => [
            'class' => 'yii\db\Connection',
            'dsn' => 'mysql:host=localhost;dbname=YourDataBaseName',
            'username' => 'root',
            'password' => '',
            'charset' => 'utf8',
        ],
```
# Run Mymart-Store
## In Crome/Your Browser
```
> mymart-Store/frontend/web
> mymart-Store/backend/web
```


DIRECTORY STRUCTURE
-------------------
```

common
    config/              contains shared configurations
    mail/                contains view files for e-mails
    models/              contains model classes used in both backend and frontend
    tests/               contains tests for common classes    
console
    config/              contains console configurations
    controllers/         contains console controllers (commands)
    migrations/          contains database migrations
    models/              contains console-specific model classes
    runtime/             contains files generated during runtime
backend
    assets/              contains application assets such as JavaScript and CSS
    config/              contains backend configurations
    controllers/         contains Web controller classes
    models/              contains backend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for backend application    
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
frontend
    assets/              contains application assets such as JavaScript and CSS
    config/              contains frontend configurations
    controllers/         contains Web controller classes
    models/              contains frontend-specific model classes
    runtime/             contains files generated during runtime
    tests/               contains tests for frontend application
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
    widgets/             contains frontend widgets
vendor/                  contains dependent 3rd-party packages
environments/            contains environment-based overrides
```
