# 🎥 VideoDemonstration 

[![App Screenshot](https://i.postimg.cc/gc8HbwYR/photo-2025-06-24-12-58-11.jpg)](https://postimg.cc/vD8VWZxH)

**VideoDemonstration** — кроссплатформенное приложение для демонстрации экрана в реальном времени через WebRTC. Идеально для презентаций, удалённой работы и совместных сессий.
> ⚠️ **Важное ограничение**: В текущей версии демонстрация экрана работает только между устройствами в **одной локальной сети**. Для работы через интернет потребуется настройка TURN-сервера или VPN.
---

## ✨ Возможности
 🖥 **Демонстрация экрана** для нескольких клиентов  
 🔍 **Гибкий выбор источника** (окно/весь экран)  
 📊 **Индикация подключения** + счётчик клиентов  
 🔄 **Автовосстановление** при разрыве связи  
 🪟 **Режим просмотра** на весь экран  
 ⚡ **Поддержка Windows/macOS/Linux**  

---

## ⚙️ Требования для разработки
| Компонент       | Минимальная версия | Рекомендуемая версия |
|-----------------|--------------------|-----------------------|
| Node.js         | v16.x              | v18.x (LTS)           |
| npm             | 7.x                | 9.x                   |
| Git             | 2.20               | 2.40+                 |
| Electron        | -                  | v26.x                 |
| Screen Capture* | -                  | Разрешение ОС         |

_* Для macOS: требуется разрешение на запись экрана в `Системные настройки → Защита и безопасность → Конфиденциальность`_

---

## 🛠 Технологии
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=flat&logo=electron&logoColor=9FEAF9)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat&logo=webrtc&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

---

## 🚀 Быстрый старт

### Клиент
```bash
git clone https://github.com/AhmedLyanov/VideoDemonstration.git
cd app
npm i 
npm start
```
### Сервер
```bash
cd server
npm install
node server.js
```
---
## 📝 Лицензия
Этот проект лицензирован под лицензией MIT.
