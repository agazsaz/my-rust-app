# my-rust-app

Лабораторная работа: настройка пайплайна CI/CD для Rust-приложения с использованием GitHub Actions и Docker.

## 1. Локальная сборка Docker
Приложение успешно компилируется и запускается в контейнере.
**<img width="1239" height="319" alt="изображение" src="https://github.com/user-attachments/assets/e3fc13d4-3f56-446f-9cb1-27eb887834a7" />**

## 2. Успешный запуск пайплайна (GitHub Actions)
Пайплайн состоит из трех последовательных джобов: `Lint & Format`, `Build & Test` и `Build Docker Image`. Все этапы завершились успешно.
**<img width="1200" height="316" alt="изображение" src="https://github.com/user-attachments/assets/901ea17d-3924-4145-a9ce-4fc10ddb45f9" />**

## 3. Логи тестирования
В джобе `Build & Test` успешно пройдены проверки типов (`cargo check`), сборка debug/release версий и запуск тестов (`cargo test`).
**<img width="647" height="168" alt="изображение" src="https://github.com/user-attachments/assets/17ce3e7f-3159-48b5-b247-fd48754d4fb4" />**




## Вывод
В ходе работы был настроен полный цикл CI для Rust-приложения. Автоматизированы проверка форматирования, линтинг (Clippy), сборка и тестирование, а также многоэтапная сборка Docker-образа. Все задачи выполнены.
