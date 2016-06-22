# FakePage
[![License](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
![Downloads](https://img.shields.io/packagist/dt/wpbp/fakepage.svg) 

Add and remove Cron job in WordPress easily!

## Install

`composer require wpbp/fakepage:dev-master`

[composer-php52](https://github.com/composer-php52/composer-php52) supported.

## Example

```php
new Fake_Page(
	array(
    'slug' => 'fake_slug',
    'post_title' => 'Fake Page Title',
    'post_content' => 'This is the fake page content'
	)
);
```

