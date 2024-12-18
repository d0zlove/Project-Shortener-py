# Project Shortener

Проект "Project Shortener" представляет собой инструмент для сокращения длинных и громоздких URL-адресов в более короткие и удобные для использования.

## Описание

"Project Shortener" разработан с целью предоставить простой и эффективный способ сокращения URL-адресов. Он позволяет пользователям вводить длинные ссылки и генерировать для них уникальные и легко запоминающиеся короткие ссылки.

## Основные функции

- Сокращение URL-адресов: Проект позволяет сокращать длинные URL-адреса в более короткие и простые для использования.
- Генерация уникальных ссылок: Каждый сгенерированный короткий URL-адрес является уникальным и не повторяется.
- Перенаправление на исходный URL: При переходе по короткому URL-адресу пользователь будет автоматически перенаправлен на исходный длинный URL-адрес.

## Технологии

Проект "Project Shortener" разработан на языке программирования Python с использованием фреймворка FastAPI. Он также использует библиотеку ctypes для взаимодействия с библиотекой C++, которая отвечает за сокращение URL-адресов.

## Установка и запуск

1. Склонируйте репозиторий проекта:

```
git clone https://gitlab.com/project-shortener/project-shortener.git
```

2. Установите зависимости:

```
pip install -r requirements.txt
```

3. Запустите проект:

```
uvicorn main:app
```

## Использование

1. Откройте веб-браузер и перейдите по адресу `http://127.0.0.1:8000`.
2. Введите длинный URL-адрес в поле ввода и нажмите кнопку "Submit".
3. Вам будет предоставлен уникальный короткий URL-адрес.
4. При переходе по короткому URL-адресу вы будете автоматически перенаправлены на исходный длинный URL-адрес.

## Авторы

- Дмитрий https://t.me/SkytNinja
- Вячеслав https://t.me/d0zlove

## Связь

Если у вас есть вопросы или предложения, свяжитесь с нами по адресу dimdimich112008@gmail.com или telegram, указаному выше.
