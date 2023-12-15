# Сайт сообщества открытого кода при ГАНОУ "Арктическая школа"

![Deploy](https://github.com/arctic-school/arctic-school.github.io/actions/workflows/deploy.yml/badge.svg)

> Прочитай CODE_OF_CONDUCT и CONTRIBUTING, перед модификацией кода.

## 🚀 Структура проекта

Внутри этого Astro проекта вы увидите следующие папки и файлы:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── ...
│   ├── layouts/
│   │   └── ...
│   └── pages/
│       └── ...
└── package.json
```

Астро ищет файлы `.astro` или `.md` в директории `src/pages/`. Каждая страница доступна как маршрут, основанный на её имени файла.

В директории `src/components/` нет ничего особенного, но это место, где мы предпочитаем размещать любые компоненты `Astro/React/Vue/Svelte/Preact`.

Любые статические ассеты, такие как изображения, могут быть помещены в директорию `public/`.

## 🧞 Как запустить сайт

Установить зависимости и запустить сайт в режиме разработчика. Веб-сервер будет доступен по `localhost:4321`.

```sh
npm install
npm run dev
```

Ещё полезные команды:

| Command                | Action                                                |
| :--------------------- | :---------------------------------------------------- |
| `npm run lint`         | Проверка чистоты кода, это обязательный процесс на CI |
| `npm run cypress:open` | Открыть консоль тестирования Cypress                  |
| `npm run build`        | Забилдить оптимизированную сборку `./dist/`           |
| `npm run preview`      | Запустить билд                                        |

## 👀 Want to learn more?

За дополнительной информацией обращайтесь к официальной документации Astro [our documentation](https://docs.astro.build).
