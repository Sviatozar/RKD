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

## Change Log

```mermaid 
gitGraph 
git checkout -b main
git commit -m "Initial commit"

git checkout -b dev
git commit -m "Initial documentation"

git checkout -b feature/backend
git commit -m "Initial Spring Boot Project"

git checkout -b hotfix/backend
git commit -m "BankController and Bank entity fixes"
git commit -m "Mapper and Repository fixes"

git checkout feature/backend
git merge hotfix/backend -m "Merge hotfix/backend into feature/backend"

git checkout dev
git merge feature/backend -m "Merge feature/backend into dev"

git checkout -b feature/frontend
git commit -m "index first ver."
git commit -m "style first ver."

git checkout dev
git merge feature/frontend -m "Merge feature/frontend into dev"
```
