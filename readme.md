# WMS 
### Windowed Management System
## Laravel-KendoUI (Web Desktop-Like Application Environment)
<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"><img src=https://telerikhelper.files.wordpress.com/2015/03/kendoui.png?w=440"></p>
<p align="center"><img src="http://www.simonecosci.com/storage/app/media/SS-1.jpg"></p>

## About WMS

WMS has been built on top of the Laravel Framework by extending some feature and using kendo-ui as frontend javascript framework.
Using this software requires a commercial license of Kendo UI

- [Laravel](https://laravel.com/docs/5.6).
- [Telerik Kendo UI for jQuery](https://www.progress.com/kendo-ui).


## Licenses

The Laravel framework and the WMS are open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

The Kendo-UI framework is commercial software licensed (https://www.telerik.com/purchase/license-agreement/kendo-ui).

## Installation

```
composer create-project --stability=dev simonecosci/wms 
cd wms
npm install
```
## Database
Creata a new database
```
mysql -uroot -p
mysql> create database yourDatabaseName;
```

Then `cp .env.example .env` and update your database creds.
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=yourDatabaseName
DB_USERNAME=root
DB_PASSWORD=root
```

Change (if you want) the initial credential by editing the file `/database/seeds/UsersTableSeeder.php` or use these:

```
email: simone.cosci@gmail.com
password: admin
```

run the migrations with seed
```
php artisan migrate:fresh --seed
```

For more info read the [Wiki](https://github.com/simonecosci/wms/wiki)

<p align="center"><img src="http://www.simonecosci.com/storage/app/media/SS-2.jpg"></p>
<p align="center"><img src="http://www.simonecosci.com/storage/app/media/SS-3.jpg"></p>
