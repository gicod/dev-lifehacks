# 🛠️ Полезные сниппеты кода и автоматизация

Сборник готовых скриптов и команд для автоматизации рутины.

---

## 📁 Лайфхак: Быстрое создание структуры папок проекта

Когда вы начинаете новый проект или создаете базу знаний, кликать мышкой и создавать папки вручную — долго. Этот сниппет позволяет создать всю структуру папок и файлов `README.md` одной строчкой кода.

### 🪟 Вариант 1. Для Windows (PowerShell)
Если вы работаете в стандартном терминале Windows или VS Code с PowerShell, скопируйте эти две команды:

```powershell
# 1. Создаем все папки разом
New-Item -ItemType Directory -Force naming, github-topics, vscode-hacks, code-snippets, microcontrollers

# 2. Создаем файлы README.md в корне и внутри каждой папки
New-Item README.md, naming/README.md, github-topics/README.md, vscode-hacks/README.md, code-snippets/README.md, microcontrollers/README.md
```

### 🍏 Вариант 2. Для macOS / Linux / Git Bash
Если вы работаете на Маке, Линуксе или используете терминал Git Bash на Windows, запустите эту команду:

```bash
mkdir -p naming github-topics vscode-hacks code-snippets microcontrollers && touch README.md naming/README.md github-topics/README.md vscode-hacks/README.md code-snippets/README.md microcontrollers/README.md
```

---

## 💡 Как адаптировать этот скрипт под другой проект
Если вам понадобится создать другую структуру (например, для сайта на React), просто замените названия папок через запятую в PowerShell или через пробел в Bash:

*   **Пример для PowerShell:** `New-Item -ItemType Directory -Force src, components, assets, public`
*   **Пример для Bash:** `mkdir -p src components assets public`

---
[🔙 На главную](../README.md)
