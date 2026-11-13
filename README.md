# Календарь бронирований

Приложение для бронирования: C++ бэкенд на Crow и интерфейс на React + Vite.

**Стек:** C++ · Crow · Boost · React · TypeScript · Vite · Tailwind CSS

## Что внутри

- `src/` — бэкенд: контроллеры, модели, работа с БД
- `src/views/frontend/` — интерфейс: календарь, форма бронирования, компоненты
- `scripts/` — сборка бэкенда
- `libs/` — зависимости C++ (Crow подключается как подмодуль)
- `booking.json` — тестовые данные

## Запуск

Бэкенд:

```bash
./scripts/make.sh
```

Фронтенд:

```bash
cd src/views/frontend
npm install
npm run start
```
