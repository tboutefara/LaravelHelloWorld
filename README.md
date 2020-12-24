# LaravelHelloWorld

## Aim

The first Laravel application.

## Some errors you may face

- **Laravel/Installer can't download Laravel packages :** you probably have an old Installer version, you must specify a news version when installing the "Installer" using Composer CLI.
- **The 500 error message :** probably you miss the .env file,
- **The Controller class can't be found :** In contrary to older version (5.x), the 8th version of Laravel needs a complete precision of the Controller class path in the route (web.php) (check the example for more details).

## What has been done in the example
 
### MyController controller created (in ./app/http/controllers)

The only controller. Created using :

`php artisan make:controller MyController`

This controller contains one function "index" that returns the "welcome" view.

### The view welcome.blade.php modified (in ./resources/views/)

Only a "Hello World" message is displayed.

### web.php toute updated (in ./routes/web.php)

The route is updated to point to the MyController controller. Notice the use of the full path of the controller in the "route" function.

