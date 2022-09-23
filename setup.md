composer create-project laravel/laravel larabreeze

composer require laravel/breeze --dev
php artisan breeze:install

php artisan migrate

composer require kamona/kui-laravel-breeze --dev
php artisan kui-breeze:replace blade

npm install & npm run build
