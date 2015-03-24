##  Facades

Enables us to write expressive, easy-to-understand code without _actually_ using static methods everywhere.

```php
$value = Cache::get('myKey');

// is equal to:

$value = $app->make('cache')->get('myKey');
```