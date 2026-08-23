# 📦 Helper Media & File Storage

<p align="center">
  <img src="https://img.shields.io/badge/Role-Public%20CDN%20Storage-blue?style=for-the-badge&logo=files" alt="CDN Storage" />
  <img src="https://img.shields.io/badge/Ecosystem-Helper%20Suite-purple?style=for-the-badge" alt="Helper Suite" />
  <img src="https://img.shields.io/badge/Shortener-TinyURL%20API-orange?style=for-the-badge" alt="TinyURL" />
</p>

Публичное хранилище медиафайлов и документов для приложения [Helper](https://github.com/domovoyproj/helper-app).

---

## 📌 Назначение

Репозиторий используется как легковесный CDN/файлообменник:
- Загрузка изображений, документов и файлов до 15 МБ через встроенный модуль в приложении Helper.
- Прямая генерация коротких ссылок через TinyURL API для удобного обмена.
- Управление и удаление файлов с синхронизацией SHA-хэшей через GitHub REST API.

---

## 📂 Структура

- `uploads/` — каталог загруженных файлов с уникальными метками времени.
