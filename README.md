# LIMINAL INSTRUMENTS

> Browser-native sound machines. Zero dependencies. Pure Web Audio API.  
> Открыл вкладку → играешь.

[🌐 Live Demo (EN)](https://ВАШ_НИК.github.io/liminal-instruments/) | [🌐 Живая версия (RU)](https://ВАШ_НИК.github.io/liminal-instruments/index-ru.html)

---

## 📡 О проекте

Коллекция из пяти автономных браузерных инструментов для саунд-дизайна и перформанса. 
Каждый инструмент — это единственный HTML-файл, который работает локально, без установки, без аккаунтов и без внешних библиотек. 
Интерфейс спроектирован как аппаратная приборная панель: фиксированный кадр, тактильный отклик, рандомизация по блокам и полная клавиатурная доступность.

## 🎛 Инструменты

| # | Инструмент | Описание | Ссылка |
|---|------------|----------|--------|
| 01 | **GRANULA** | Liminal granular workstation. True stereo grain cloud, time freezing, polyphony. | [Open](./Granula.html) |
| 02 | **NULLROOM Ø** | Liminal ambient workstation. 100 presets, 16×8 sequencer, generative scenes. | [Open](./NullRoom.html) |
| 03 | **MUTABLE•WEB XL** | Modular synthesizer. 20 modules, CV everywhere, patch cables, generative ambient. | [Open](./MutableWeb.html) |
| 04 | **OCTA//WEB** | Performance sampler. 16-step knob automation, A/B scenes, morph crossfader. | [Open](./OktaWeb.html) |
| 05 | **NEUROGRID** | OP–IDM drum & synth machine. 8 voices, polymetric 16×8 sequencer, parameter locks. | [Open](./NeuroGrid.html) |

## ⚙️ Системные требования

- **Движок**: Web Audio API
- **Зависимости**: 0 (Zero)
- **Установка**: Не требуется (Single File)
- **Офлайн-режим**: Да (работает с локального диска или флешки)
- **Экспорт**: WAV (audio), JSON (patches)
- **Браузеры**: Chrome, Edge, Safari, Firefox (последние версии)

## ⌨️ Глобальное управление (на лендинге)

- `1` ... `5` : Открыть соответствующий инструмент в новой вкладке
- `↑` / `↓` : Навигация по рэку
- `ENTER` : Запустить выбранный инструмент
- `S` : Включить/выключить фоновый эмбиент-дрон сайта
- `R` : Выбрать случайный инструмент (⚄)
- `?` : Открыть руководство оператора

## 📂 Структура репозитория

```text
.
├── index.html          # Лендинг (English)
├── index-ru.html       # Лендинг (Русский)
├── Granula.html        # Гранулярный синтез
├── NullRoom.html       # Эмбиент и генератив
├── MutableWeb.html     # Модулярная среда
├── OktaWeb.html        # Сэмплер и автоматизация
└── NeuroGrid.html      # Полиметрический секвенсор