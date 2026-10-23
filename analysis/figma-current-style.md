# Figma audit · current Avito presentation

Дата анализа и синхронизации: 23 октября 2026.

Источник: https://www.figma.com/design/YLrOv4c3BpgE27DoG4V5zQ/Untitled?node-id=0-1

## Исходный аудит

- 53 верхнеуровневых исходных слайда.
- Каждый слайд: 1920×1080.
- 708 текстовых слоёв.
- Основной шрифт по всем повторяющимся стилям: Manrope.
- До нормализации в файле не было локальных Text/Paint/Grid Styles и Variables.

## Нормализация, выполненная после аудита

Создана отдельная page:
- **STYLE GUIDE · AVITO SP**
- node `2025:65`

Создана collection:
- **AVITO / Presentation**
- `VariableCollectionId:2025:66`
- 20 variables

Созданы 11 text styles `AVITO /` на базе Manrope.

Созданы 6 specimen frames:
- `2026:66` — Core rules
- `2026:76` — Typography
- `2026:95` — Colors & surfaces
- `2026:125` — Grid & layout
- `2026:145` — KPI & cards
- `2026:161` — Visual language

Валидация: 75/75 текстовых слоёв style guide используют Manrope.

## Частые типографические значения исходника

Наиболее повторяемые размеры: 35, 30, 73, 40, 45, 41, 31, 39, 26, 38, 70 px.

Ключевой заголовочный паттерн: Manrope SemiBold 73 px.
Основной body-паттерн: Manrope Regular/Medium 35 px.
Частое letter-spacing: -2%.

## Частые координаты

Самый частый левый anchor текста: x=50 px.
Самый частый верхний anchor: y=60 px.

Также регулярно встречаются колоночные anchors около 700, 1015 и 1310 px.

## Карточки

На репрезентативных светлых KPI-слайдах:
- большие карточки: радиус 40 px;
- внутренние KPI-ячейки: радиус 40 px;
- типовая ширина большой KPI-карточки ≈590 px;
- типовая ширина внутренней KPI-ячейки ≈180 px.

На плотных dashboard-слайдах:
- небольшие карточки часто используют радиус 20 px;
- крупные группирующие контейнеры — 40 px.

Выраженные drop-shadow на проверенных светлых слайдах не обнаружены.

## Основные режимы

**Light:** #ECF3FA + #1E1E1E + белые карточки + #5B89C6/#00AAFF.

**Dark:** синий линейный градиент + белый текст + glass-панели + яркий cyan.

## Репрезентативные исходные Figma-слайды

- 6 — Before / After
- 8 — Product launch + smartphones
- 14 — dark KPI / marketing
- 17 — KPI execution cards
- 20 — product screens
- 31 — transaction KPI
- 36 — typographic hero + status cards
- 46 — dense dashboard

При спорных решениях сначала использовать repo rules, затем specimen page и эти исходные референсы.
