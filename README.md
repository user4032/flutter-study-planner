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

## Як почати

1. Клонувати репозиторій:
```bash
git clone https://github.com/<твій-нік>/student-diary.git
Встановити Flutter пакети:

flutter pub get
Запустити проєкт:

flutter run
План розвитку
 Базова структура проєкту

 CRUD для розкладу

 CRUD для нотаток

 Теми (світла/темна)

 Push notifications

 iOS Widget


---

## 4️⃣ Наступні кроки для GitHub

1. Створити репозиторій `student-diary`.
2. Додати `README.md` з текстом вище.
3. Додати `.gitignore` для Flutter:

build/
.dart_tool/
.packages
.idea/
.vscode/


4. Ініціалізувати репозиторій:

```bash
git init
git add .
git commit -m "Initial commit: setup project structure and README"
git branch -M main
git remote add origin https://github.com/<твій-нік>/student-diary.git
git push -u origin main
