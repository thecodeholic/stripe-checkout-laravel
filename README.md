# Stripe checkout process in Laravel

The purpose of this repo is to show you all the necessary steps you should follow to implement complete and correct stripe checkout flow. 
This repo is created alongside with the [YouTube Tutorial](https://youtube.com/[ID]).

## Full Flow

<img src="https://raw.githubusercontent.com/thecodeholic/stripe-checkout-laravel/main/Stripe_Checkout_Flow.png" alt="Stripe Checkout Flow" />

## Installation & Setup

1. Clone the repository
1. Copy `.env.example` into `.env`
1. Login to your stripe dashboard, take your secret key and put it in `.env`.
1. Go to the project root directory and run `composer install`
1. Run `php artisan key:generate --ansi` to generate key in .env file
1. create empty file under `database/database.sqlite`
1. Run migrations and seed `php artisan migrate`
1. Run `php artisan serve` which will start server at http://localhost:8000



## Laravel Sponsors

Support my work by [Buying me a beer](https://buymeacoffee.com/thecodeholic) or [becoming a patron](https://www.patreon.com/thecodeholic).


