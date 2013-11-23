## Installation

Begin by installing this package through Composer. Edit your project's `composer.json` file to require `varmad/laravel-haml`.

It might look something like:

```php
  "require": {
    "laravel/framework": "4.0.*",
    "varmad/laravel-haml": "dev-master",
  }
```

Next, update Composer from the Terminal:

```php
    composer update
```

Once this operation completes, add the service provider. Open `app/config/app.php`, and add a new item to the providers array.

```php
    'Varmad\LaravelHaml\LaravelHamlServiceProvider'
```


## Usage
Creating a view file

        filename.haml.php(hello.haml.php)

Rendering form the controller 

        public function index() {
		return View::make('hello');
	}


