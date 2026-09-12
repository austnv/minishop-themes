# 🌊 Aurora — Полярное сияние

Спокойная, гипнотическая тема в духе ночного неба над Исландией. Волны полярного сияния медленно текут по горизонтали, звёзды мерцают, панели — матовое стекло.

## 📸 Превью

![Aurora preview](./preview.webp)

## ✨ Особенности

- **Живое полярное сияние** — два слоя волн, нарисованных через `mask-image: radial-gradient()`, движутся по горизонтали в разные стороны. Скорость 180s и 300s на цикл — эффект «дыхания».
- **Звёздное небо** — меньше звёзд, чем в Universe, но крупнее (1.2–1.8px) и ярче. Лёгкое мерцание.
- **Матовое стекло** — `backdrop-filter: blur(24px) saturate(140%)` + низкая прозрачность (0.45–0.55). Фон просвечивает сквозь панели.
- **Тройной градиент логотипа** — бирюза → зелёный → индиго, `background-clip: text` + плавный сдвиг `background-position`.
- **Мягкое свечение активных элементов** — пульсирующая точка, `box-shadow: inset`, зелёный градиент слева.
- **Уважение к `prefers-reduced-motion`** — все анимации отключаются.
- **Облегчение на мобильных** — второй слой волн убирается, blur снижается, звёздный тайл мельче.

## 🎨 Токены

### Основные цвета

| Токен | Значение | Плашка | Использование |
|---|---|---|---|
| `accent` | `#5eead4` | ![#5eead4](https://img.shields.io/badge/-5eead4?style=flat-square) | Главный акцент, ссылки, активные элементы |
| `accent_secondary` | `#22c55e` | ![#22c55e](https://img.shields.io/badge/-22c55e?style=flat-square) | Середина градиента, прогресс |
| `accent_tertiary` | `#818cf8` | ![#818cf8](https://img.shields.io/badge/-818cf8?style=flat-square) | Конец градиента, info-состояния |
| `bg_base` | `#050a14` | ![#050a14](https://img.shields.io/badge/-050a14?style=flat-square) | Базовый фон |
| `bg_panel` | `#080e18` (α .55) | ![#080e188C](https://img.shields.io/badge/-080e188c?style=flat-square) | Панели, карточки |
| `bg_sidebar` | `#080e18` (α .45) | ![#080e1873](https://img.shields.io/badge/-080e1873?style=flat-square) | Сайдбар |
| `bg_elevated` | `#0e1624` (α .75) | ![#0e1624BF](https://img.shields.io/badge/-0e1624bf?style=flat-square) | Модалки, дропдауны |

### Текст и состояния

| Токен | Значение | Плашка | Использование |
|---|---|---|---|
| `text_primary` | `#e2e8f0` | ![#e2e8f0](https://img.shields.io/badge/-e2e8f0?style=flat-square) | Основной текст |
| `text_secondary` | `#94a3b8` | ![#94a3b8](https://img.shields.io/badge/-94a3b8?style=flat-square) | Второстепенный текст |
| `text_muted` | `#64748b` | ![#64748b](https://img.shields.io/badge/-64748b?style=flat-square) | Placeholder, подписи |
| `border` | `#5eead4` (α .12) | ![#5eead41F](https://img.shields.io/badge/-5eead41f?style=flat-square) | Границы панелей |
| `border_strong` | `#5eead4` (α .25) | ![#5eead440](https://img.shields.io/badge/-5eead440?style=flat-square) | Активные границы |
| `success` | `#22c55e` | ![#22c55e](https://img.shields.io/badge/-22c55e?style=flat-square) | Успех |
| `warning` | `#fbbf24` | ![#fbbf24](https://img.shields.io/badge/-fbbf24?style=flat-square) | Предупреждение |
| `danger` | `#f87171` | ![#f87171](https://img.shields.io/badge/-f87171?style=flat-square) | Ошибка |
| `info` | `#818cf8` | ![#818cf8](https://img.shields.io/badge/-818cf8?style=flat-square) | Информация |

## 🎨 Палитра

| Цвет | HEX | Плашка | Где встречается |
|---|---|---|---|
| Бирюзовый | `#5eead4` | ![#5eead4](https://img.shields.io/badge/-5eead4?style=flat-square) | Акцент, ссылки, кнопки, активный пункт |
| Светлая бирюза | `#7df1dc` | ![#7df1dc](https://img.shields.io/badge/-7df1dc?style=flat-square) | Hover ссылок, скроллбар |
| Зелёный | `#22c55e` | ![#22c55e](https://img.shields.io/badge/-22c55e?style=flat-square) | Градиент, success, прогресс |
| Светлый зелёный | `#34d973` | ![#34d973](https://img.shields.io/badge/-34d973?style=flat-square) | Hover скроллбара |
| Индиго | `#818cf8` | ![#818cf8](https://img.shields.io/badge/-818cf8?style=flat-square) | Конец градиента, info |
| Ночной фон | `#050a14` | ![#050a14](https://img.shields.io/badge/-050a14?style=flat-square) | Базовый фон |
| Панель | `#080e18` | ![#080e18](https://img.shields.io/badge/-080e18?style=flat-square) | Панели, карточки |
| Возвышенный | `#0e1624` | ![#0e1624](https://img.shields.io/badge/-0e1624?style=flat-square) | Модалки |
| Текст | `#e2e8f0` | ![#e2e8f0](https://img.shields.io/badge/-e2e8f0?style=flat-square) | Основной текст |
| Текст мягкий | `#94a3b8` | ![#94a3b8](https://img.shields.io/badge/-94a3b8?style=flat-square) | Второстепенный текст |
| Текст приглушённый | `#64748b` | ![#64748b](https://img.shields.io/badge/-64748b?style=flat-square) | Placeholder |
| Жёлтый | `#fbbf24` | ![#fbbf24](https://img.shields.io/badge/-fbbf24?style=flat-square) | Warning |
| Красный | `#f87171` | ![#f87171](https://img.shields.io/badge/-f87171?style=flat-square) | Danger |

## 🎬 Градиенты

| Название | CSS | Где применяется |
|---|---|---|
| Aurora (основной) | `linear-gradient(135deg, #5eead4 0%, #22c55e 35%, #818cf8 70%, #5eead4 100%)` | Акценты, логотип |
| Кнопка primary | `linear-gradient(135deg, #5eead4 0%, #22c55e 100%)` | `.btn-primary` |
| Прогресс | `linear-gradient(90deg, #5eead4 0%, #22c55e 60%, #818cf8 100%)` | Заливка `.progress` |
| Активный пункт | `linear-gradient(90deg, rgba(94,234,212,0.14) 0%, rgba(34,197,94,0.06) 60%, transparent 100%)` | `.sidebar-item.active` |
| Скроллбар | `linear-gradient(180deg, #5eead4, #22c55e)` | Thumb |
| Волна сияния 1 | `linear-gradient(180deg, transparent 0%, rgba(94,234,212,0.14) 22%, rgba(34,197,94,0.10) 42%, rgba(129,140,248,0.07) 62%, transparent 88%)` | `.aurora-waves` |
| Волна сияния 2 | `linear-gradient(180deg, transparent 8%, rgba(129,140,248,0.10) 28%, rgba(94,234,212,0.07) 52%, rgba(34,197,94,0.05) 72%, transparent 92%)` | `.aurora-waves-2` |

## 🔤 Шрифты

| Роль | Семейство | Fallback | Пример |
|---|---|---|---|
| Sans (UI) | Inter | system-ui, sans-serif | Основной текст |
| Logo | Inter | system-ui, sans-serif | Логотип, заголовки |
| Mono | JetBrains Mono | ui-monospace, monospace | Код, цифры |

Шрифты подтягиваются MiniShop через токены `font_sans`, `font_logo`, `font_mono`. В CSS используется `var(--font-ui)` — не `var(--font-sans)`.

## 📁 Структура

```
themes/aurora/
├── LICENSE
├── README.md
├── theme.json
├── style.css
└── preview.webp
```

## 🌗 Варианты

**Один вариант — `dark`.** Aurora концептуально — ночное небо. Light-вариант разрушил бы идею полярного сияния и добавил бы пользователю лишний переключатель. Тема одинаково хороша и днём, и ночью благодаря тёмному фону.

## ⚙️ Установка

Через админ-панель MiniShop → **Настройки → Темы → Установить из Git**:

```
URL:      https://git.uvpn.app/austnv/minishop-themes
Ветка:    master
Подпапка: themes/aurora
```

ZIP в репозитории не хранится — MiniShop собирает пакет сам из подпапки.

## 📝 Лицензия

MIT — см. [LICENSE](./LICENSE).