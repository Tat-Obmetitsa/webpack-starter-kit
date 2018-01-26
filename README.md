# Для работы сборки, необходимо установить **LTS** версию [NodeJS](https://nodejs.org/en/)

## Использование

* Скачать репо как архив
* Переименовать папку под свой проект
* В консоли перейти в корень проекта
* Выполнить команду **npm i**
* Ждать пока установятся все зависимости
* В index.js есть пример как импортировать стили

## Dev и Prod

* **npm start** запускает режим разработки
* **npm run build** запускает режим сборки в продакшн, создастся папка dist

## Папки и файлы

* **src** - тут лежат исходники
* **src/index.html** - шаблон под результирующий html-файл, можно смело редактировать. В продакшене сюда автоматически добаввятся теги link и script для css и js
* **src/index.js** - точка входа в приложение, сюда импортируем все остальное
* **dist** - автоматически создастся в продакшене, тут будут готовые файлы

## ParcelJS

Тем кому не хочется влезать в вебпак рекомендую [https://parceljs.org/](https://parceljs.org/)