# Vanilla Modal with HTML and CSS

Простий, доступний та адаптивний модальний компонент, реалізований за допомогою нативних HTML та CSS. Проєкт демонструє використання тега `<dialog>` у поєднанні з сучасними стилями для створення легкої модальної реалізації без сторонніх бібліотек чи фреймворків.

---

## Основні можливості

- **Нативний тег `<dialog>`**:
  Використовує вбудований функціонал браузера для створення модальних вікон, що забезпечує простоту та високу продуктивність.

- **Адаптивний дизайн**:
  Повністю адаптований до різних розмірів екранів, включно з мобільними пристроями.

- **Доступність**:
  Використовує ARIA-атрибути (`aria-labelledby`, `aria-label`) для покращення підтримки екранних зчитувачів.

- **Плавні анімації**:
  CSS-анімації забезпечують стильний ефект появи та закриття модального вікна.

- **Легкість**:
  Для роботи не потрібні сторонні бібліотеки чи фреймворки.

---

## Структура коду

### HTML

- **Кнопка для відкриття модального вікна**:
  Кнопка з атрибутом `onclick`, яка викликає метод `showModal()` для відкриття модального вікна.
- **Контент модального вікна**:
  Тег `<dialog>` містить форму для функціоналу закриття та простір для контенту (заголовок і текст).

### CSS

- **Глобальні стилі**:
  Включають скидання стилів та базову типографіку.
- **Анімації модального вікна**:
  Плавні переходи для з’явлення модального вікна та ефектів backdrop за допомогою CSS `transition` та `cubic-bezier`.
- **Адаптивність**:
  Медійні запити забезпечують зручне відображення на малих екранах.
- **Інтерактивні стилі кнопок**:
  Ефекти наведення та фокусу для кнопок забезпечують покращений користувацький досвід.

---

## Як це працює

1. **Відкриття модального вікна**:

   - Метод `showModal()` активується натисканням кнопки, відкриваючи модальне вікно та блокуючи фоновий контент.

2. **Закриття модального вікна**:
   - Форма всередині модального вікна використовує атрибут `method="dialog"`, який автоматично закриває вікно після сабміту.