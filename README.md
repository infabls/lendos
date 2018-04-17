# Boilerplate for simple onepage website 
***
[Author website](https://infabls.com)
### Installing
```html
git clone https://github.com/infabls/lendos.git
npm install
composer install
```
### Dependencies

Зависимости объявлены явно в файлах package.json и composer.json

Необходим gulp, sass, node js

### Structure
```html
/public - здесь лежит то, что доступно через URL
  /assets  
    /img  
    /css  
    /js  
/engine  
  /func
/сonfig  - тут конфигурируется приложение
/app - здесь ведётся разработка приложения
```
### Назначение файлов
Название файла  | Содержание файла
----------------|----------------------
style.css       | Пустой файл каскадной таблицы стилей, в который производится сбока необходимых стилей
reset.css       | Reset CSS от Эрика Мейера
normalize.css   | Нормалайзер CSS от Nicolas Gallagher
block.css       | Основные стили блоков системы
addition.css    | Дополнительные стили
fontawesome.css | Стили иконочного шрифта
layout.css      | Основные стили, применительно к определённому сайту
lightbox.css    | Стили лайтбокса, если таковой используется
index.html      | Индексный файл для проверки вносимых изменений
