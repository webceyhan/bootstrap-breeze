## Introduction

Breeze provides a minimal and simple starting point for building a Laravel 10 application with authentication. Breeze publishes authentication controllers and views to your application that can be easily customized based on your own application's needs.

Bootstrap Breeze is powered by Inertia, Vue 3 and Bootstrap 5 and replacing TailwindCSS. 

Getting started couldn't be easier:

```bash
laravel new my-app --breeze

# choose inertia + vue stack (+ tailwindcss by default)

cd my-app

composer require webceyhan/bootstrap-breeze --dev

php artisan breeze:vue-bootstrap

npm install && npm run dev
```
