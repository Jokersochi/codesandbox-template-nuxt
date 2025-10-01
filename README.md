# Nuxt 2 Template

Готовый шаблон проекта на Nuxt 2 (static target) с поддержкой TypeScript, Jest, ESLint и Prettier.

## Требования

- Node.js 14+ (рекомендуется LTS)
- Yarn 1.x

## Установка

```bash
yarn install
```

## Скрипты

- `yarn dev` — локальная разработка на `http://localhost:3000`
- `yarn build` — сборка продакшн-бандла
- `yarn start` — запуск собранного приложения
- `yarn generate` — генерация статического сайта в `dist/`
- `yarn test` — запуск Jest тестов
- `yarn lint` — проверка ESLint + Prettier
- `yarn lintfix` — авто-правки форматирования и линтинга

## Структура

- `pages/` — входные страницы приложения (из коробки обновлённая `index.vue`)
- `components/` — Vue-компоненты (оставлен пример `NuxtLogo.vue`)
- `store/` — (опционально) Vuex
- `test/` — тесты для Jest

Удалён демо-компонент `components/Tutorial.vue`.

## Быстрый старт

```bash
yarn dev
```

Откройте `pages/index.vue` и начинайте разработку.

## Полезные ссылки

- [Nuxt 2 — Документация](https://nuxtjs.org/docs)
- [Nuxt — GitHub](https://github.com/nuxt/framework)
