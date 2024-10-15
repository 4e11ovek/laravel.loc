## Установка из репозитория ## 
```sh
git clone https://github.com/4e11ovek/laravel.loc.git
```
Перейти в папку с рпоктом и устоновить композер зависимостей
```sh
cd laravel.loc
```
```sh
composer install
```
Скопировать файл .env.example и переименовать в .env
```sh
cp.env.example .env
```
Сгенерировать ключи шифрования
```sh
php artisan key:generate
```
Изменить файл конфигурации .env
