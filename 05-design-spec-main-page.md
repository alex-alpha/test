# Design Spec: B2B Portal - Main Page (Desktop)

## Canvas Settings
- Width: 1920px
- Height: ~4000px (scrollable)
- Background: #FFFFFF
- Grid: 12 columns, 80px gutter

---

## 1. HEADER (Sticky)

**Position:** x:0, y:0, w:1920, h:80

**Container:** x:160, y:0, w:1600, h:80

**Logo:**
- x:160, y:20, w:120, h:40
- Text: "АЛЬФА" or Image: Alfa logo
- Color: #2C3E50 (dark blue-gray)

**Navigation:**
- x:320, y:28, w:800, h:24
- Items: Услуги | Решения | Контент | О нас | Контакты
- Font: Inter 16px Regular
- Color: #4A5568 (gray)
- Spacing: 40px between items

**CTA Button (Personal Cabinet):**
- x:1440, y:16, w:160, h:48
- Background: #3498DB (primary blue)
- Radius: 8px
- Text: "Личный кабинет"
- Font: Inter 16px Medium
- Color: #FFFFFF

**Phone:**
- x:1240, y:28, w:160, h:24
- Text: "+7 (812) 467-34-77"
- Font: Inter 16px Regular
- Color: #2C3E50

---

## 2. HERO SECTION

**Position:** x:0, y:80, w:1920, h:720

**Background:**
- Gradient: Linear 135deg
- From: #667EEA (purple-blue)
- To: #764BA2 (deep purple)
- Or use subtle pattern overlay

**Container:** x:160, y:160, w:800, h:560

**Headline:**
- x:160, y:200, w:800, h:120
- Text: "B2B порталы\nпод ключ"
- Font: Inter 64px Bold
- Line height: 1.2
- Color: #FFFFFF

**Subheadline:**
- x:160, y:340, w:600, h:80
- Text: "Создание и аренда B2B порталов с интеграцией 1С и автоматизацией бизнес-процессов"
- Font: Inter 20px Regular
- Line height: 1.5
- Color: #E2E8F0

**CTA Buttons:**
- Primary:
  - x:160, y:440, w:200, h:56
  - Background: #FFFFFF
  - Radius: 8px
  - Text: "Рассчитать стоимость"
  - Font: Inter 18px Medium
  - Color: #667EEA

- Secondary:
  - x:380, y:440, w:160, h:56
  - Border: 2px solid #FFFFFF
  - Radius: 8px
  - Text: "Смотреть кейсы"
  - Font: Inter 18px Medium
  - Color: #FFFFFF

**Trust Badges:**
- x:160, y:520, w:600, h:40
- Items in row:
  - ✓ Интеграция 1С
  - ✓ 14 дней запуск
  - ✓ Техподдержка 24/7
- Font: Inter 16px Regular
- Color: #E2E8F0

**Hero Image/Graphic:**
- x:1120, y:120, w:640, h:560
- Abstract B2B illustration or dashboard mockup
- Opacity: 0.9

---

## 3. KEY ADVANTAGES (3-6 cards)

**Position:** x:0, y:800, w:1920, h:400

**Container:** x:160, y:800, w:1600, h:400

**Section Title:**
- x:160, y:800, w:600, h:40
- Text: "Почему выбирают нас"
- Font: Inter 32px Bold
- Color: #2C3E50

**Cards Grid:** 3 columns

**Card 1:**
- x:160, y:880, w:480, h:280
- Background: #FFFFFF
- Border: 1px solid #E2E8F0
- Radius: 16px
- Padding: 32px

  **Icon:** 48x48px, #667EEA
  **Title:** "Интеграция 1С", Inter 20px Bold
  **Description:** "Полная синхронизация данных с 1С Предприятие, Битрикс и другими системами", Inter 16px Regular, #4A5568

**Card 2:**
- x:680, y:880, w:480, h:280
- Same structure
- Title: "Аренда от 15500₽"
- Description: "Готовые решения под ключ или аренда B2B портала с минимальными вложениями"

**Card 3:**
- x:1200, y:880, w:480, h:280
- Same structure
- Title: "Быстрый запуск"
- Description: "Запуск портала за 14 дней с полной настройкой и обучением команды"

---

## 4. SERVICES PREVIEW

**Position:** x:0, y:1280, w:1920, h:600

**Container:** x:160, y:1280, w:1600, h:600

**Section Title:**
- Text: "Наши услуги"
- Font: Inter 32px Bold
- Color: #2C3E50

**Service Cards (4 in row):**

**Service 1:**
- x:160, y:1360, w:360, h:480
- Background: #F7FAFC
- Radius: 12px
- Title: "Создание B2B портала"
- Description: "Индивидуальная разработка под ваш бизнес"
- CTA: "Подробнее →"

**Service 2:**
- x:560, y:1360, w:360, h:480
- Title: "Аренда кабинета"
- Description: "От 15500₽/месяц, готовое решение"

**Service 3:**
- x:960, y:1360, w:360, h:480
- Title: "Модули для B2B"
- Description: "Контрагенты, скидки, бонусы, прайс-листы"

**Service 4:**
- x:1360, y:1360, w:360, h:480
- Title: "Интеграции"
- Description: "1С, Битрикс, ERP, CRM системы"

---

## 5. VIDEO CONTENT SECTION

**Position:** x:0, y:1960, w:1920, h:800

**Background:** #F7FAFC

**Container:** x:160, y:1960, w:1600, h:800

**Section Title:**
- Text: "Видео материалы"
- Subtitle: "Узнайте больше о B2B порталах из наших видео"
- Font: Inter 32px Bold
- Color: #2C3E50

**Video Cards (3 in row):**

**Video 1:**
- x:160, y:2080, w:480, h:320
- Thumbnail: Your video thumbnail
- Title: "Работа с прайс-листами"
- Duration: "12:34"
- CTA: "Смотреть"

**Video 2:**
- x:680, y:2080, w:480, h:320
- Title: "Интеграция с 1С"
- Duration: "15:20"

**Video 3:**
- x:1200, y:2080, w:480, h:320
- Title: "Функционал менеджера"
- Duration: "10:45"

**Link to all videos:**
- x:160, y:2440, w:200, h:40
- Text: "Все видео →"
- Color: #667EEA

---

## 6. CONTENT/BLOG PREVIEW (SEO)

**Position:** x:0, y:2840, w:1920, h:600

**Container:** x:160, y:2840, w:1600, h:600

**Section Title:**
- Text: "Полезные материалы"
- Subtitle: "Статьи, глоссарий и инструкции по B2B порталам"
- Link: "Весь контент →"

**Article Cards (3 in row):**

**Article 1:**
- x:160, y:2960, w:480, h:400
- Image header
- Tag: "Интеграция"
- Title: "Модуль B2B-KTR: выгрузка контрагентов"
- Author: "Александр", Date: "23.04.2026"
- Excerpt: "Полная синхронизация контрагентов, менеджеров и условий..."

**Article 2:**
- x:680, y:2960, w:480, h:400
- Tag: "Аренда"
- Title: "Аренда b2b-портала или Интернет-магазина"

**Article 3:**
- x:1200, y:2960, w:480, h:400
- Tag: "Техническое"
- Title: "Техническая реализация b2b портала"

---

## 7. COMPACT CALCULATOR

**Position:** x:0, y:3520, w:1920, h:400

**Background:** #667EEA

**Container:** x:160, y:3520, w:1600, h:400

**Title:**
- Text: "Рассчитайте стоимость вашего B2B портала"
- Font: Inter 28px Bold
- Color: #FFFFFF

**Calculator Form:**
- x:480, y:3600, w:960, h:240
- Background: #FFFFFF
- Radius: 16px

  **Field 1:** Select "Тип проекта"
  **Field 2:** Select "Аренда / Покупка"
  **Field 3:** Select "Масштаб"
  **Button:** "Рассчитать" → shows price

---

## 8. CTA SECTION

**Position:** x:0, y:3920, w:1920, h:320

**Container:** x:160, y:3920, w:1600, h:320

**Title:**
- Text: "Готовы обсудить ваш проект?"
- Font: Inter 32px Bold
  Color: #2C3E50

**Contact Options:**
- Form: Name, Email, Message, "Отправить"
- Phone: +7 (812) 467-34-77
- Email: info@s-alpha.ru

---

## 9. FOOTER

**Position:** x:0, y:4240, w:1920, h:240

**Background:** #2C3E50

**Container:** x:160, y:4240, w:1600, h:240

**Columns:**
1. Company (logo, about)
2. Services (links)
3. Content (articles, glossary)
4. Contact (phone, email, address)
5. Social (VK, Telegram)

**Bottom:**
- Copyright © 2026 ООО "АЛЬФА"
- Privacy Policy
- Terms of Service

---

## COLOR PALETTE

### Primary
- Dark Blue: #2C3E50
- Purple Blue: #667EEA
- Deep Purple: #764BA2

### Secondary
- Gray Light: #F7FAFC
- Gray: #E2E8F0
- Gray Dark: #4A5568

### Accent
- Primary Blue: #3498DB
- Success Green: #48BB78
- Warning Orange: #ED8936

### Neutral
- White: #FFFFFF
- Black: #1A202C

---

## TYPOGRAPHY

### Font Family
- Primary: Inter
- Fallback: system-ui, sans-serif

### Sizes
- H1: 64px Bold (hero)
- H2: 32px Bold (sections)
- H3: 24px SemiBold (cards)
- H4: 20px Medium (subheads)
- Body: 16px Regular
- Small: 14px Regular
- Caption: 12px Regular

### Line Heights
- Headings: 1.2
- Body: 1.5
- Small: 1.4

---

## SPACING SYSTEM

- Base unit: 8px
- Scale: 8, 16, 24, 32, 40, 48, 64, 80, 120, 160

---

## COMPONENTS

### Buttons
- Primary: bg-primary, text-white, radius-8, h:48-56
- Secondary: border-2, text-primary, radius-8, h:48-56
- Ghost: transparent, text-primary, radius-8, h:48-56

### Cards
- bg-white, border-gray, radius-12-16, padding-32
- Shadow: 0 4px 6px rgba(0,0,0,0.05)

### Inputs
- bg-white, border-gray, radius-8, h:48, padding: 12 16
- Focus: border-primary

### Tags
- bg-primary-light, text-primary, radius-4, padding: 4 12
