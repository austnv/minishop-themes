# 🌌 Universe

Космический скин для MiniShop. Тёмное пространство, мерцающие звёзды, туманности, стеклянные панели, тонкие светящиеся линии.

## 📸 Превью

![Universe preview](./preview.png)

## ✨ Особенности

- **Анимированный космический фон** — два слоя звёзд и три туманности, медленно дрейфуют по диагонали.
- **Кометы** — раз в 45–60 секунд через экран пролетает светящаяся точка.
- **Матовое стекло** — панели, карточки и модалки используют `backdrop-filter: blur()`.
- **Пульсирующие акценты** — активный пункт меню подсвечен слева, справа — мигающая точка.
- **Переливающийся логотип** — градиент плавно течёт от голубого к фиолетовому.
- **Топливные прогресс-бары** — с бегущим световым бликом по заливке.
- **Уважение к `prefers-reduced-motion`** — пользователи с ограничениями по анимации получат спокойную версию.
- **Оптимизация под мобильные** — тяжёлые эффекты отключаются, меню подсвечивается мягко.

## 🎨 Токены

### Основные цвета

| Токен        | Значение             |                                                                                    Плашка                                                                                    | Использование                                                                |
| ----------------- | ---------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | ----------------------------------------------------------------------------------------- |
| `accent`        | `#5cc8ff`                  |        <span style="display:inline-block;width:60px;height:20px;background:#5cc8ff;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span>        | «Реактор» интерфейса — свечения, границы, кнопки |
| `bg`            | `#02040a`                  |        <span style="display:inline-block;width:60px;height:20px;background:#02040a;border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>        | Вакуум — почти чёрный с холодным оттенком              |
| `panel`         | `#080e18`                  |        <span style="display:inline-block;width:60px;height:20px;background:#080e18;border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>        | Основная панель                                                             |
| `panel_2`       | `#0d1521`                  |        <span style="display:inline-block;width:60px;height:20px;background:#0d1521;border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>        | Вложенная панель                                                           |
| `panel_3`       | `#141f2e`                  |        <span style="display:inline-block;width:60px;height:20px;background:#141f2e;border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>        | Всплывающие элементы, тосты                                       |
| `border`        | `rgba(92, 200, 255, 0.14)` | <span style="display:inline-block;width:60px;height:20px;background:rgba(92,200,255,0.14);border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Обычные границы                                                             |
| `border_strong` | `rgba(92, 200, 255, 0.32)` | <span style="display:inline-block;width:60px;height:20px;background:rgba(92,200,255,0.32);border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Акцентные границы                                                         |

### Текст и состояния

| Токен | Значение |                                                                             Плашка                                                                             | Использование                                                        |
| ---------- | ---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------: | --------------------------------------------------------------------------------- |
| `text`   | `#eaf3fb`      |    <span style="display:inline-block;width:60px;height:20px;background:#eaf3fb;border:1px solid rgba(0,0,0,0.2);border-radius:4px;vertical-align:middle;"></span>    | Основной текст                                                       |
| `muted`  | `#7d92ab`      |    <span style="display:inline-block;width:60px;height:20px;background:#7d92ab;border:1px solid rgba(0,0,0,0.2);border-radius:4px;vertical-align:middle;"></span>    | Второстепенный текст                                           |
| `dim`    | `#465a73`      | <span style="display:inline-block;width:60px;height:20px;background:#465a73;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Приглушённый текст                                               |
| `danger` | `#ff5c7c`      | <span style="display:inline-block;width:60px;height:20px;background:#ff5c7c;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Ошибки и предупреждения                                      |
| `blue`   | `#5cc8ff`      | <span style="display:inline-block;width:60px;height:20px;background:#5cc8ff;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Информационные сообщения (совпадает с`accent`) |

## 🎨 Палитра

Все цвета, которые встречаются в теме — включая те, что используются только внутри CSS, но не объявлены как токены.

| Цвет                                  | Hex                           |                                                                                    Плашка                                                                                    | Где встречается                                                                 |
| ----------------------------------------- | ----------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | --------------------------------------------------------------------------------------------- |
| Небесно-голубой             | `#5cc8ff`                   |        <span style="display:inline-block;width:60px;height:20px;background:#5cc8ff;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span>        | Основной акцент: границы, свечения, иконки, логотип |
| Голубой неон                   | `#00e5ff`                   |        <span style="display:inline-block;width:60px;height:20px;background:#00e5ff;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span>        | Заливка прогресс-баров, второй стоп градиента          |
| Фиолетовый                      | `#a78bfa`                   |        <span style="display:inline-block;width:60px;height:20px;background:#a78bfa;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span>        | Второй стоп градиента логотипа, туманность               |
| Глубокий синий               | `#2b7fff`                   |        <span style="display:inline-block;width:60px;height:20px;background:#2b7fff;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span>        | Нижний стоп кнопок, вторичный акцент                           |
| Вакуум                              | `#02040a`                   |        <span style="display:inline-block;width:60px;height:20px;background:#02040a;border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>        | Основной фон                                                                       |
| Глубокий космос             | `#080e18`                   |        <span style="display:inline-block;width:60px;height:20px;background:#080e18;border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>        | Панели                                                                                  |
| Приглушённый красный   | `#ff5c7c`                   |        <span style="display:inline-block;width:60px;height:20px;background:#ff5c7c;border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span>        | Ошибки и предупреждения                                                  |
| Звёздный белый               | `rgba(255, 255, 255, 0.9)`  |    <span style="display:inline-block;width:60px;height:20px;background:rgba(255,255,255,0.9);border:1px solid rgba(0,0,0,0.2);border-radius:4px;vertical-align:middle;"></span>    | Звёзды, текст на кнопках                                                  |
| Стекло панелей               | `rgba(8, 14, 24, 0.75)`     |   <span style="display:inline-block;width:60px;height:20px;background:rgba(8,14,24,0.75);border:1px solid rgba(255,255,255,0.3);border-radius:4px;vertical-align:middle;"></span>   | Фон карточек, модалок, сайдбара                                     |
| Туманность голубая       | `rgba(92, 200, 255, 0.10)`  | <span style="display:inline-block;width:60px;height:20px;background:rgba(92,200,255,0.10);border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Первая туманность на фоне                                               |
| Туманность фиолетовая | `rgba(167, 139, 250, 0.09)` | <span style="display:inline-block;width:60px;height:20px;background:rgba(167,139,250,0.09);border:1px solid rgba(255,255,255,0.2);border-radius:4px;vertical-align:middle;"></span> | Вторая туманность на фоне                                               |

## 🎬 Градиенты

| Название                 | CSS                                                                                       | Где применяется                                                                   |
| -------------------------------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Шиммер логотипа    | `linear-gradient(270deg, #5cc8ff, #a78bfa, #00e5ff, #a78bfa, #5cc8ff)`                  | Переливающийся текст логотипа и заголовков                |
| Реактор кнопки      | `linear-gradient(135deg, #5cc8ff, #2b7fff)`                                             | Основные кнопки действия                                                  |
| Топливная шкала    | `linear-gradient(90deg, #5cc8ff, #00e5ff)`                                              | Заливка прогресс-баров                                                      |
| Блик по прогрессу | `linear-gradient(90deg, transparent, rgba(255,255,255,0.55), transparent)`              | Анимированный пробегающий блик                                      |
| Проблеск кнопки    | `linear-gradient(120deg, transparent 30%, rgba(255,255,255,0.25) 50%, transparent 70%)` | Световая полоса, проходящая по кнопке при наведении |

## 🔤 Шрифты

| Роль                            | Семейство | Fallback                                               | Плашка стиля                                                                                             |
| ----------------------------------- | ------------------ | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| UI                                  | `Inter`          | `-apple-system, BlinkMacSystemFont, Segoe UI, Arial` | <span style="font-family:Inter,sans-serif;">Пример текста интерфейса</span>                   |
| Логотип / заголовки | `Orbitron`       | `Michroma, Inter`                                    | <span style="font-family:Orbitron,Michroma,sans-serif;letter-spacing:2px;text-transform:uppercase;">Universe</span> |
| Моноширинный            | `JetBrains Mono` | `ui-monospace, SFMono-Regular, Menlo, Consolas`      | <span style="font-family:'JetBrains Mono',monospace;">token: </span>                                                |

Шрифты не поставляются с темой — MiniShop подтягивает их по токенам `font_sans`, `font_logo`, `font_mono`.

## 📁 Структура

```
themes/universe/
├── LICENSE          # MIT (копия корневого)
├── README.md        # Этот файл
├── theme.json       # Конфиг MiniShop
├── style.css        # Все стили темы
└── preview.webp     # Превью 1280×800
```

## 🌗 Варианты

Тема объявляет **только** вариант `dark`. Переключатель light/dark у пользователя не появится — космос всегда космос.

## ⚙️ Установка

### Через Git

```
URL:      https://git.uvpn.app/austnv/minishop-themes
Ветка:    master
Подпапка: themes/universe
```

## 📝 Лицензия

MIT — см. [LICENSE](./LICENSE).
