# Student Diary

**Student Diary** — особистий щоденник для студентів, який допомагає організувати розклад пар, вести нотатки, отримувати нагадування та переглядати розклад через віджет на iOS.

## Основні функції

- Додавання та видалення пар
- Замінa пар на конкретний день
- Показ часу пар та назв предметів
- Додавання нотаток (домашнє завдання, підготовка до пари)
- Світла та темна тема
- Push-сповіщення перед парою
- Віджет iOS із розкладом та нагадуваннями

## Структура проекту
lib/
├─ main.dart
├─ theme/
│ └─ app_theme.dart
├─ models/
│ ├─ lesson.dart
│ └─ note.dart
├─ screens/
│ ├─ home_screen.dart
│ ├─ schedule_screen.dart
│ └─ notes_screen.dart
├─ widgets/
│ ├─ lesson_tile.dart
│ ├─ note_tile.dart
│ └─ calendar_widget.dart
├─ services/
│ ├─ db_service.dart
│ └─ notification_service.dart
└─ utils/
└─ date_utils.dart
## Технології

- Flutter / Dart
- Hive / SQLite для локального збереження даних
- Provider / Riverpod для управління станом
- Flutter WidgetKit для iOS віджета
- Git + GitHub для спільної роботи
