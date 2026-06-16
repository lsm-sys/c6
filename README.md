# c6

Браузерный калькулятор.

## Локальный запуск

```powershell
pnpm dev
```

Откройте http://localhost:3000

## Деплой на Vercel

### Через CLI

1. Установите Vercel CLI (один раз):

```powershell
pnpm add -g vercel
```

2. Войдите в аккаунт:

```powershell
vercel login
```

3. Деплой:

```powershell
pnpm deploy
```

Для preview-деплоя без флага `--prod`:

```powershell
vercel
```

### Через GitHub

1. Загрузите репозиторий на GitHub.
2. Импортируйте проект на [vercel.com/new](https://vercel.com/new).
3. Vercel автоматически определит статический сайт — сборка не требуется.
4. Каждый push в основную ветку будет автоматически деплоиться.

## Структура

- `index.html` — главная страница (калькулятор)
- `calculator.html` — дубликат, редирект на `/`
- `vercel.json` — конфигурация Vercel
