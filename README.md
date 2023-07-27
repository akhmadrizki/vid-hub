# Video Hub
> Based on [Laravel v10](https://laravel.com)

## Table of contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Database setup](#database-setup)
- [Running the app](#running-the-app)

## Prerequisites

- PHP ≥ 8.1
- Node ≥ 16.10

If Using VSCode Please install these extensions on your code editor :

- [laravel intellisense](https://marketplace.visualstudio.com/items?itemName=mohamedbenhida.laravel-intellisense)
- [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)

## Setup
1. Clone This Repository:
```sh
$ git clone [https://github.com/(your username)/market-management-program.git](https://github.com/akhmadrizki/vid-hub.git)
```
2. Copy file `.env.example` to `.env`:
```sh
$ cp env-example .env
```
3. Install all package
```sh
$ composer install
```

## Database setup

```sh
...
DB_DATABASE=db_market
DB_USERNAME=root
DB_PASSWORD=
...
```

- Run this command:
```sh
$ php artisan key:generate
$ composer dump-autoload
$ php artisan migrate:fresh --seed
$ php artisan storage:link
```

## Running the app

```sh
$ php artisan serve
```
