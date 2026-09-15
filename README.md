# Максим Семёнов

**Python Developer**

Студент 4 курса факультета информационных технологий, специальность «Информационные системы и технологии в игровой индустрии».

- 📞 +375 (33) 375-25-**
- ✉️ m.s.semenov@students.psu.by
- 💻 github.com/[maximusgeng](https://github.com/maximusgeng)

---

## Стек

![Python](https://img.shields.io/badge/Python%203-3776AB?style=flat&logo=python&logoColor=white)
![tkinter](https://img.shields.io/badge/tkinter-стандартная_библиотека-blue)
![socket](https://img.shields.io/badge/socket%20%2B%20threading-сеть_и_потоки-blue)
![numpy](https://img.shields.io/badge/numpy-013243?style=flat&logo=numpy&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-визуализация-orange)
![openpyxl](https://img.shields.io/badge/openpyxl-XLSX-green)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

Основной инструмент — Python и стандартная библиотека: `tkinter`, `socket`, `threading`, `json`, `re`, `collections`, `datetime`. Из сторонних — `numpy`, `matplotlib`, `openpyxl`. Дополнительно — C# / Unity.

---

## Проекты

### 📡 Монитор неисправностей датчиков автомобиля (Python)

Десктоп-приложение на tkinter: принимает телеметрию по UDP в фоновом потоке либо загружает логи из XLSX, в реальном времени детектирует неисправности — обрывы датчиков, залипание сигнала, аномалии уровня топлива, рассинхрон колёс ABS.

- Сеть и многопоточность: `socket` (UDP) + `threading`, потокобезопасные кольцевые буферы на `collections.deque`
- Детекция аномалий на скользящих окнах с гистерезисом и дебаунсом событий
- Парсинг XLSX через `openpyxl` с автоопределением колонок и временной шкалы
- Графики `matplotlib` (TkAgg), встроенные в интерфейс, с отметками аномалий
- Журнал неисправностей с группировкой по категориям и датчикам

### ⚔️ [Fight! — 3D мультиплеерный файтинг](https://github.com/maximusgeng/3d-multiplayer-fighting-game) *(Unity, курсовой проект)*

Unity 6 · C# · Mirror (KCP) · Rigidbody. Сетевой файтинг по LAN, PC + Android.

- Серверная боевая логика (урон, блок, победа последнего выжившего) через `Command` / `ClientRpc` / `SyncVar`
- Лобби, точки спавна, рестарт матча; анимации на Animation Events + `NetworkAnimator`

### 🌫️ [Lighthouse — 3D-сцена с интерактивным светом](https://github.com/maximusgeng/lighthouse-3d-scene) *(Unity + Blender)*

Unity 6 (URP) · Blender · Particle System.

- Модели окружения в Blender, сборка сцены в Unity
- Динамический туман на частицах, интерактивные источники света

---

## Чем полезен

- Python: десктоп-приложения с GUI, сетевые приложения (UDP/TCP), многопоточность, обработка данных и логов
- C# / Unity: геймплей, физика, сетевой мультиплеер на Mirror
- Blender → Unity: подготовка 3D-контента
