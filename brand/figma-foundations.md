# Figma foundations · Авито Спецтехника

Актуально на 23 октября 2026.

## Рабочий Figma

File key: `YLrOv4c3BpgE27DoG4V5zQ`

Style guide page:
- name: **STYLE GUIDE · AVITO SP**
- page node: `2025:65`

## Specimen frames

| Экран | Node ID | Назначение |
| --- | --- | --- |
| SG 01 · CORE RULES | `2026:66` | источник истины, базовые правила |
| SG 02 · TYPOGRAPHY | `2026:76` | Manrope type scale |
| SG 03 · COLORS & SURFACES | `2026:95` | палитра и поверхности |
| SG 04 · GRID & LAYOUT | `2026:125` | anchors, margins, columns, gutters |
| SG 05 · KPI & CARDS | `2026:145` | KPI-карточки и радиусы |
| SG 06 · VISUAL LANGUAGE | `2026:161` | do/don't и визуальный язык |

Все specimen frames: **1920×1080**.

## Variables

Collection:
- **AVITO / Presentation**
- ID: `VariableCollectionId:2025:66`
- current variable count: **20**

Переменные:
- `color/bg/light`
- `color/text/primary`
- `color/text/inverse`
- `color/surface/white`
- `color/surface/near-black`
- `color/brand/blue`
- `color/brand/deep-blue`
- `color/accent/cyan`
- `color/accent/purple`
- `color/accent/green`
- `color/status/positive`
- `color/status/alert`
- `color/neutral/300`
- `color/surface/blue-20`
- `color/surface/blue-40`
- `space/20`
- `space/40`
- `space/60`
- `radius/20`
- `radius/40`

## Text styles

Созданы локальные стили:
- `AVITO / Hero 130`
- `AVITO / Slide Title 73`
- `AVITO / Slide Title 70`
- `AVITO / Subsection 51`
- `AVITO / Card Title 44`
- `AVITO / Body 35`
- `AVITO / Body Medium 35`
- `AVITO / Dense 30`
- `AVITO / Caption 25`
- `AVITO / Micro 20`
- `AVITO / KPI 99`

Все стили используют **Manrope**.

## Обязательный workflow для дальнейшей работы

1. Сначала читать актуальные правила из репозитория.
2. Затем открывать Figma page `2025:65`.
3. Для цветов, радиусов и spacing использовать collection **AVITO / Presentation**, а не вводить значения вручную.
4. Для текста использовать локальные `AVITO /` text styles.
5. При создании нового слайда сначала выбирать ближайший композиционный паттерн из `brand/layouts.md`.
6. Если Figma и репозиторий расходятся, остановиться и считать **репозиторий источником истины**; Figma привести к нему.
7. Старый PDF использовать только как исторический референс.

## Валидация

После создания foundations проверено:
- 6 specimen frames;
- 75 текстовых слоёв;
- 75/75 текстовых слоёв используют Manrope;
- 20 local variables;
- 11 local AVITO text styles;
- визуальная проверка основных specimen frames пройдена без заметного клиппинга и перекрытий.
