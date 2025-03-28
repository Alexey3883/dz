# 🚀 Основные команды Git

Этот файл содержит список наиболее часто используемых команд Git для быстрого старта работы с системой контроля версий.

## 🔧 Базовые операции

| Команда | Описание |
|---------|----------|
| `git init` | Инициализирует новый репозиторий Git |
| `git clone <url>` | Клонирует удаленный репозиторий |
| `git status` | Показывает состояние рабочей директории |

## ✨ Работа с изменениями

```bash
# Добавление изменений
git add <file>    # Добавить конкретный файл
git add .         # Добавить все изменения

# Фиксация изменений
git commit -m "Описание изменений"

# Просмотр истории
git log           # Полная история коммитов
git log --oneline # Краткая история

🌿 Ветвление

# Создание и переключение веток
git branch <branch-name>      # Создать новую ветку
git checkout <branch-name>    # Переключиться на ветку (старый способ)
git switch <branch-name>      # Переключиться на ветку (новый способ)

# Слияние веток
git merge <branch-name>       # Объединить ветки

☁️ Работа с удаленным репозиторием

# Настройка удаленного репозитория
git remote add origin <url>

# Синхронизация изменений
git push -u origin <branch>   # Отправить изменения
git pull                      # Получить изменения

⏪ Отмена изменений

git restore <file>        # Отменить изменения в файле
git reset <file>         # Отменить индексацию файла
git reset --soft HEAD~1  # Отменить последний коммит
