# Пользовательская установка Windows

Инструменты и ресурсы для создания настраиваемых установок Windows.

## Автоматическая установка Windows

### Генератор Unattend для Windows

[Генератор Unattend для Windows](https://schneegans.de/windows/unattend-generator/) - полезный инструмент для создания пользовательских установок Windows.

#### Функции:

- Генерация файлов unattend.xml для автоматизированных установок Windows
- Настройка параметров установки (язык, часовой пояс, разбиение на разделы)
- Пропуск экранов настройки Windows
- Предварительная настройка учетных записей пользователей

#### Как использовать:

1. Посетите веб-сайт генератора
2. Настройте желаемые параметры
3. Загрузите сгенерированный файл unattend.xml
4. Поместите его в правильное место на носителе установки Windows

Этот инструмент особенно полезен для:

- Создания стандартизированных развертываний
- Экономии времени при повторяющихся установках
- Настройки виртуальных машин

#### Моя сборочка:

[Скачать мой autounattend.xml](https://github.com/rafabduloff/qol/blob/main/assets/autounattend.xml)
