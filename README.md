# security-audit-checklist

Stop missing security issues in code! This repo provides a step-by-step checklist for auditing Python, Bash, and C/C++ projects. From dangerous `os.system()` calls to SUID bit risks — everything in one place. Contribute and improve security practices together.

## Содержание репозитория
- Поиск прямых системных вызовов (Python, Bash, C/C++).
- Проверка прав выполнения (Linux/macOS, Windows).
- Анализ обработки ошибок.
- Инструменты статического анализа.
- Тестирование под нагрузкой.
- Мониторинг системных вызовов.

## Для кого этот чек-лист?
- Разработчики, которые хотят повысить безопасность своих скриптов.
- DevOps-инженеры, настраивающие CI/CD с проверками безопасности.
- Аудиторы, проводящие ревью кода.

## Как использовать?
1. Пройдите по разделам последовательно.
2. Применяйте чек-лист как шаблон для аудита.
3. Используйте примеры кода для быстрого внедрения исправлений.

## Структура папок
security-audit-checklist/
├── README.md
├── 1-system-calls/
│ ├── python.md
│ ├── bash.md
│ └── c-cpp.md
├── 2-permissions/
│ ├── linux-macos.md
│ └── windows.md
├── 3-error-handling/
│ └── python.md
├── 4-static-analysis/
│ ├── python.md
│ ├── bash.md
│ └── c-cpp.md
├── 5-load-testing/
│ └── scenarios.md
├── 6-system-monitoring/
│ ├── linux.md
│ ├── windows.md
│ └── macos.md
└── CHECKLIST.md

## Как внести вклад?
- Предлагайте новые примеры для языков/платформ.
- Добавляйте кейсы из реального опыта.      
- Исправляйте неточности.

## Лицензия
MIT
- Исправляйте неточности.

## Лицензия
