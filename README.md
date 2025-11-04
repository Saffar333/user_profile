# Telegram Profile Mini App

Мини-приложение для отображения профиля пользователя Telegram.

## Деплой на Vercel

### Вариант 1: Через веб-интерфейс

1. Загрузите всю папку `telegram-profile-app` в Git репозиторий (GitHub, GitLab, Bitbucket)
2. Зайдите на [vercel.com](https://vercel.com)
3. Нажмите "Add New Project"
4. Импортируйте ваш репозиторий
5. Vercel автоматически определит настройки
6. Нажмите "Deploy"

### Вариант 2: Через Vercel CLI

```bash
npm install -g vercel
cd telegram-profile-app
vercel
```

### Вариант 3: Drag & Drop

1. Зайдите на [vercel.com](https://vercel.com)
2. Перетащите папку `telegram-profile-app` в область загрузки
3. Готово!

## Настройка в BotFather

После деплоя получите URL (например, `https://your-app.vercel.app`) и выполните:

```
1. Откройте @BotFather в Telegram
2. Отправьте команду: /newapp
3. Выберите вашего бота
4. Введите название приложения
5. Введите описание
6. Загрузите фото (640x360px)
7. Введите URL: https://your-app.vercel.app
```

Готово! Теперь можете открыть Web App через вашего бота.

## Отображаемые данные

- Telegram ID
- Имя
- Фамилия
- Полное имя
- Username
- Язык интерфейса
- Premium статус
- Разрешения бота
- Тип чата
- Платформа
- Версия Web App
- Цветовая схема

## Локальная разработка

```bash
python -m http.server 8000
```

Откройте: http://localhost:8000

## Требования

- Telegram Bot (создайте через @BotFather)
- Vercel аккаунт (бесплатный)
- Git репозиторий (опционально)

## Структура проекта

```
telegram-profile-app/
├── index.html         # Главная страница профиля
├── vercel.json        # Конфигурация Vercel
├── package.json       # Метаданные проекта
├── .vercelignore      # Игнорируемые файлы
└── README.md          # Документация
```
