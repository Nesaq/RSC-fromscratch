## Ref

[React Server Components без фреймворка](https://intermediate-react-v6.holt.courses/lessons/rscs-without-a-framework/the-rsc-server)

# RSC-fromscratch

Этот проект демонстрирует использование React Server Components (RSC) с нуля, с настройкой серверной части на Node.js и использованием Babel для транспиляции кода.

## Структура проекта

- `server/main.js` — основной входной файл сервера, настраивает окружение для React Server Components и Babel.
- `server/server.js` — основной серверный код.

## Установка

1. Клонируйте репозиторий:

2. Установите зависимости:
   ```bash
   npm install
   ```

## Запуск

Используйте команды:

```bash
npm run dev:server
npm run dev:client
```

## Описание работы

- Используется пакет `react-server-dom-webpack` для поддержки React Server Components.
- Babel на лету транспилирует серверный код, игнорируя папки `dist`, `server` и `node_modules`.
- Сервер запускается из файла `server/server.js`.

## Требования

- Node.js (рекомендуется последняя LTS-версия)
- npm
