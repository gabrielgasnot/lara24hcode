## Startup

Run
```
composer update
```
And 
```
npm install
```

This will install the defaults packages (php & javascript).

Then run 
```
npm run dev
```

This will compile your javascript/sass/less files.

You'll also have to copy ".env.example" to ".env" and run the following command :
```
php artisan key:generate
```

You can then test the projet :
```
php artisan serve
```

## Errors
## Errors

If you can't start the application, take a look at "/storage/logs/laravel.log"
