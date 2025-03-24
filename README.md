# SF_-Database

## 📌 О проекте

Этот репозиторий содержит учебные задания по работе с базами данных PostgreSQL, разбитые на 4 модуля. Каждый модуль включает:
- Скрипт инициализации БД (`DB_Initialisation_Part_X.sql`)
- Скрипты с решениями задач (`DB_Task_N.sql`)


## 📂 Структура проекта
```
SF_DB_Tasks/
├── SF_DB_1/ # Модуль 1 (2 задачи)
│ ├── DB_Initialisation_Part_1.sql
│ ├── DB_Task_1.sql
│ └── DB_Task_2.sql
├── SF_DB_2/ # Модуль 2 (5 задач)
│ ├── DB_Initialisation_Part_2.sql
│ ├── DB_Task_1.sql
│ ├── DB_Task_2.sql
│ ├── DB_Task_3.sql
│ ├── DB_Task_4.sql
│ └── DB_Task_5.sql
├── SF_DB_3/ # Модуль 3 (3 задачи)
│ ├── DB_Initialisation_Part_3.sql
│ ├── DB_Task_1.sql
│ ├── DB_Task_2.sql
│ └── DB_Task_3.sql
└── SF_DB_4/ # Модуль 4 (3 задачи)
  ├── DB_Initialisation_Part_4.sql
  ├── DB_Task_1.sql
  ├── DB_Task_2.sql
  └── DB_Task_3.sql
```

## 🚀 Быстрый старт

1. **Создайте БД**:
```
CREATE DATABASE practice_db;
```
2. **Подключитесь**:
```
    psql -U postgres -d mydatabase
```
3. **Выполните скрипты**:
 - `DB_Initialisation_Part_X.sql`  - сначала инициализация
 - `DB_Task_X.sql`                 - затем задачи

⚠️ Важные заметки

 - Требуется PostgreSQL 12+
 - База создается отдельно командой CREATE DATABASE
 - Скрипты выполняются строго по порядку
