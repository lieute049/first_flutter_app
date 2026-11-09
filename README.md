# Flutter Lab3 — Hello World

Простое Flutter-приложение с градиентным фоном и стилизованным текстом. Первый проект на Flutter.

## Автор

Куксова Софья, ИСП-243

## Стек и версии

- **Flutter:** 3.47.9 (stable)
- **Dart:** 3.13.7
- **Платформа:** Web (Edge)
- **IDE:** VS Code

## Скриншот

![Приложение](img/step9_Kuksova.png)

## Запуск

1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/lieute049/first_flutter_app.git
   ```
2. Перейти в папку:
   ```bash
   cd first_flutter_app
   ```
3. Установить зависимости:
   ```bash
   flutter pub get
   ```
4. Запустить:
   ```bash
   flutter run -d edge
   ```

## Что изучили

- структура Flutter-проекта
- дерево виджетов: `MaterialApp → Scaffold → Container → Center → Text`
- Hot Reload (`r`) и Hot Restart (`R`)
- оформление: `Container`, `BoxDecoration`, `LinearGradient`, `TextStyle`