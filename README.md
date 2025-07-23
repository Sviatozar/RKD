# RKD
Development Documentation

# Spring Boot Application

Цей проєкт є базовою структурою для створення сучасного застосунку з використанням фреймворку **Spring Boot**.

## 🔧 Можливості

- Модульна архітектура
- Гнучка конфігурація
- Підтримка REST API
- Інтеграція зі сторонніми сервісами
- Розширюваність під потреби проєкту

## 🚀 Запуск проєкту

1. Клонуйте репозиторій:
   ```bash
   git clone https://github.com/Sviatozar/RKD

## 📦 Збірка
Для збірки використовуйте:

   ./mvnw clean package

## 📄 Ліцензія
Цей проєкт розповсюджується під відкритою ліцензією. Умови використання див. у файлі LICENSE

## 📁 Структура проєкту
src   
├── main    
│   ├── java   
│   └── resources       
└── test 


## Change Log

Front: було розроблено дві версії інтерфейсу для додатку
також було підібрано  сучасний та гарний стиль

Back: Розроблено багатошаровий Spring Boot проєкт,
що включає контролери, сервіри, репозиторії для роботи з базою даних.

## Історія комітів
```mermaid
gitGraph
   commit id: "Initial commit" tag: "main"
   branch dev
   checkout dev
   commit id: "Initial documentation"

   branch feature/backend
   checkout feature/backend
   commit id: "Initial Spring Boot Project"

   branch hotfix/backend
   checkout hotfix/backend
   commit id: "BankController and Bank entity fixes"
   commit id: "Mapper and Repository fixes"

   checkout feature/backend
   merge hotfix/backend id: "Merge hotfix/backend into feature/backend"

   checkout dev
   merge feature/backend id: "Merge feature/backend into dev"

   branch feature/frontend
   checkout feature/frontend
   commit id: "index first ver."
   commit id: "style first ver."

   checkout dev
   merge feature/frontend id: "Merge feature/frontend into dev"

   checkout main
   merge dev id: "Merge dev into main"
```

