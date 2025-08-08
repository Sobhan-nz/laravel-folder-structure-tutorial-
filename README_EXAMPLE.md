# 📂Example Project Laravel

An example project has been designed for you, dear ones. Follow the instructions below and the HelloController.php and web.php files.

---

### 1. `Create Project`

```bash
composer create-project laravel/laravel laravel-folder-structure-demo
```
---
### 2. `Create a simple controller`

```bash
php artisan make:controller HelloController
```

`app/Http/Controllers/HelloController.php`
```php
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class HelloController extends Controller
{
    public function index()
    {
        return "Hello, Laravel Folder Structure!";
    }
}
```
---
### 4. `Project implementation`
```bash
php artisan serve
```
Now, by going to `http://127.0.0.1:8000/hello`, the text will be displayed.

---
### 5. `Output and folders`
This project now has all the folders you described in the blog:
- `app/`
- `bootstrap/`
- `config/`
- `database/`
- `public/`
- `resources/`
- `routes/`
- `storage/`
- `tests/`
- And core files like `.env`, `artisan`, `composer.json`
