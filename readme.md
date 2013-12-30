Laravel Boilerplate
===
A starting point for every Laravel project. It will include:

- Assets
	- Grunt: concat, minify and cachebusting
	- Blade syntax and helper functions
	- On the fly image resize and crop and responsive image implementation (https://github.com/kevbaldwyn/image)
- Deploy
	- Capistrano (why can't I get Rocketeer to work?)
- Authentication
	- Login
	- Register
	- Password Reset
- Admin Panel
	- User Management
- Base Classes
	- Repository
- Packages
	- Kint debug tool
	- Laravel-debugbar
- Notifications
- Layouts

Setup instructions
---
1. Clone the repo
2. Run composer install
3. Run php artisan key:generate
5. Configure database
6. Run php artisan migrate
7. Run php artisan seed
8. Add hostname and domain pattern to bootstrap/start.php

Laravel PHP Framework
---

[![Latest Stable Version](https://poser.pugx.org/laravel/framework/version.png)](https://packagist.org/packages/laravel/framework) [![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.png)](https://packagist.org/packages/laravel/framework) [![Build Status](https://travis-ci.org/laravel/framework.png)](https://travis-ci.org/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, and caching.

Laravel aims to make the development process a pleasing one for the developer without sacrificing application functionality. Happy developers make the best code. To this end, we've attempted to combine the very best of what we have seen in other web frameworks, including frameworks implemented in other languages, such as Ruby on Rails, ASP.NET MVC, and Sinatra.

Laravel is accessible, yet powerful, providing powerful tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

## Official Documentation

Documentation for the entire framework can be found on the [Laravel website](http://laravel.com/docs).

### Contributing To Laravel

**All issues and pull requests should be filed on the [laravel/framework](http://github.com/laravel/framework) repository.**

### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)