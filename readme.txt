php artisan make:authe

-- create mysql DB - multirolelogin

php artisan make:migration create_admins_table --create=admins

Duplicate User Model apps/User.php

Modify config/authe.php and add admin guard

Modify routes/web.php and add routes for AdminController
Route::get('/admin', 'AdminController@index')->name('home');

Create copy of resources/views/home.blade.php => admin.blade.php

php artisan make:controller AdminController

php artisan make:controller AdminController

php artisan make:controller AdminController