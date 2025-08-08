# 📂پروژه نمونه لاراول

یک پروژه نمونه برای شما عزیزان طراحی شده است. دستورالعمل‌های زیر و فایل‌های `HelloController.php` و `web.php` را دنبال کنید.

---

### 1. `ایجاد پروژه`

```bash
composer create-project laravel/laravel laravel-folder-structure-demo
```
---
### 2. `ایجاد یک کنترلر ساده`

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
### 4. `پیاده‌سازی پروژه`
```bash
php artisan serve
```
حالا با رفتن به `http://127.0.0.1:8000/hello`، متن نمایش داده می‌شود.

---
### 5. `خروجی و پوشه‌ها`
این پروژه اکنون تمام پوشه‌هایی را که در وبلاگ توضیح داده‌اید، دارد:
- `app/`
- `bootstrap/`
- `config/`
- `database/`
- `public/`
- `resources/`
- `routes/`
- `storage/`
- `tests/`
- و فایل‌های اصلی مانند `.env`، `artisan`، `composer.json`
