## Storage Laravel Provider

[![Latest Stable Version](https://poser.pugx.org/carlosocarvalho/storage-cloudinary-laravel/v/stable)](https://packagist.org/packages/carlosocarvalho/storage-cloudinary-laravel) [![Total Downloads](https://poser.pugx.org/carlosocarvalho/storage-cloudinary-laravel/downloads)](https://packagist.org/packages/carlosocarvalho/storage-cloudinary-laravel) [![Latest Unstable Version](https://poser.pugx.org/carlosocarvalho/storage-cloudinary-laravel/v/unstable)](https://packagist.org/packages/carlosocarvalho/storage-cloudinary-laravel) [![License](https://poser.pugx.org/carlosocarvalho/storage-cloudinary-laravel/license)](https://packagist.org/packages/carlosocarvalho/storage-cloudinary-laravel)

Install via composer

```json
    
    composer require carlosocarvalho/storage-cloudinary-laravel
    
```

  Configure config/filesystems.php
```php
   
   
   'cloudinary' => [
               'driver' => 'cloudinary',
               'api_key' => env('CLOUDINARY_API_KEY'),
               'api_secret' => env('CLOUDINARY_API_SECRET'),
               'cloud_name' => env('CLOUDINARY_CLOUD_NAME'),
           ],
   
```

  Add the service provider to the providers array in config/app.php
```php
    CarlosOCarvalho\Providers\CloudinaryServiceProvider::class
```
