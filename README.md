# Auth Optional Laravel Api

This package will provide to login as user or login as a guest, so we will describe the package


## Usage

```php
    protected $routeMiddleware = [
        'auth.optional' => \App\Http\Middleware\AuthOptional::class
    ];
```