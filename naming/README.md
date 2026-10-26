# 🏷️ Шпаргалка по неймингу проектов и репозиториев

Правильное имя проекта — это отсутствие багов в консоли, красивые ссылки в браузере и порядок на компьютере.

---

## 🛑 Золотой стандарт оформления: kebab-case
Всегда пишите названия **только строчными (маленькими) английскими буквами, разделяя слова дефисом (`-`)**.

*   ❌ `My-Project` (заглавные буквы ломают URL)
*   ❌ `Cool_App` (нижние подчеркивания не считываются поисковиками как разделители)
*   ❌ `Diplom 2026` (пробелы превратятся в уродливые `%20` в адресной строке)
*   ❌ `тестовый-сайт` (кириллица превращается в кракозябры в терминале)

---

## 🛠️ Формула идеального имени
Чтобы легко автоматизировать создание репозиториев через ваш будущий сайт, используйте структуру:
> **`[тип-проекта]-[технология/стек]-[суть-проекта]`**

---

## 📁 50+ примеров по категориям для копирования

### 🖥️ Frontend & Веб-сайты
1. `landing-html-barbershop` — Лендинг парикмахерской на чистом HTML/CSS
2. `landing-nextjs-crypto` — Промо-страница криптопроекта на Next.js
3. `portfolio-react-minimal` — Минималистичный сайт-портфолио на React
4. `site-vue-restaurant` — Многостраничный сайт ресторана на Vue
5. `site-astro-blog` — Быстрый контентный блог на Astro
6. `app-react-dashboard` — Панель администратора (админка) на React
7. `app-angular-crm` — CRM-система для бизнеса на Angular
8. `widget-js-weather` — Виджет погоды на чистом JavaScript
9. `theme-tailwind-dark` — Кастомная темная тема на Tailwind CSS

### ⚙️ Backend & API
10. `api-node-ecommerce` — REST API для интернет-магазина на Node.js
11. `api-python-delivery` — Бэкенд для службы доставки на FastAPI
12. `api-go-chat` — Высоконагруженный сервер для чата на Go
13. `api-laravel-blog` — Движок для блога на PHP/Laravel
14. `service-auth-jwt` — Микросервис авторизации через JWT-токены
15. `db-postgres-migrations` — Схемы и миграции базы данных PostgreSQL
16. `graphql-apollo-server` — Сервер GraphQL на Apollo

### 📱 Mobile Apps (Мобилки)
17. `app-flutter-tracker` — Трекер привычек на Flutter
18. `app-rn-fitness` — Приложение для фитнеса на React Native
19. `app-ios-swift-notes` — Заметки для iOS на Swift
20. `app-android-kotlin-crypto` — Криптокошелек для Android на Kotlin

### 🎮 Games (Игры)
21. `game-unity-runner` — Раннер-игра на движке Unity
22. `game-godot-platformer` — 2D-платформер на Godot
23. `game-js-canvas-snake` — Змейка на чистом JavaScript (Canvas)
24. `game-unreal-shooter` — Шутер от первого лица на Unreal Engine

### 🤖 Автоматизация, Скрипты & ML
25. `bot-telegram-feedback` — Telegram-бот для обратной связи
26. `bot-discord-moderator` — Бот-модератор для Discord
27. `parser-python-avito` — Парсер объявлений с Avito на Python
28. `script-bash-backup` — Скрипт автоматического бэкапа базы данных
29. `script-node-images` — Скрипт для массового сжатия картинок
30. `ml-python-housing` — Модель прогнозирования цен на жилье
31. `ai-openai-summarizer` — Инструмент для суммаризации текста через API

### 📚 Учеба & Песочницы (Sandbox)
32. `course-skillbox-frontend` — Домашние работы по курсу Frontend
33. `tutorial-react-redux` — Проект-туториал по изучению Redux
34. `sandbox-js-async` — Песочница для тестирования асинхронного JS
35. `leetcode-solutions-js` — Мои решения задач на LeetCode
36. `test-docker-compose` — Тестовый запуск контейнеров в Docker
37. `demo-stripe-integration` — Демо-интеграция платежной системы Stripe

### 📦 Шаблоны & Библиотеки
38. `template-webpack-vanilla` — Стартовая сборка Webpack + чистый JS
39. `template-nextjs-tailwind` — Шаблон Next.js с настроенным Tailwind
40. `lib-js-validator` — Собственная библиотека для валидации форм
41. `plugin-wp-seo` — Кастомный SEO-плагин для WordPress
42. `extension-chrome-adblock` — Расширение для браузера Chrome

### 🔧 DevOps & Инфраструктура
43. `docker-node-mongo` — Готовая Docker-сборка Node.js + MongoDB
44. `ansible-web-server` — Скрипты автоматической настройки веб-сервера
45. `github-actions-cicd` — Шаблоны для автоматического деплоя проектов
46. `k8s-cluster-config` — Конфигурационные файлы для Kubernetes

### 🛠️ Hardware & Электроника
47. `mcu-arduino-smart-home` — Прошивка умного дома на Arduino
48. `mcu-esp32-weather-station` — Метеостанция с Wi-Fi на ESP32
49. `mcu-stm32-drone` — Полетный контроллер квадрокоптера на STM32
50. `mcu-raspberry-cam` — Скрипт видеонаблюдения для Raspberry Pi

---

## 🚫 Чек-лист: Чего делать нельзя
1.  **Никаких версий в названии.** Забудьте про `my-project-v2`, `final-clear`, `super-final`. Для версий в Git есть коммиты и теги (Tags). Название папки всегда должно оставаться чистым: `my-project`.
2.  **Никаких заглавных букв и пробелов.**

---
[🔙 На главную](../README.md)
