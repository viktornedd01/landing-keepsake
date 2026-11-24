# Keepsake - landing

Адаптивна вебсторінка Keepsake за макетом у Figma

**Демо** https://viktornedd01.github.io/landing-keepsake/

# Технології

- HTML;
- CSS;
- Figma
- Шрифти з Google Fonts: Oswald, Open Sans, Dancing Script;
- Зображення у WebP;
- Squosh

# Рішення

- Дизайн-токени (кольори, розміри шрифтів, відступи) винесені в CSS-змінні в :root;
- Мобільне меню без використання Java Script: прихований чекбокс, label і :checked ~;
- Форма підписки: HTML-валідація, помилка через :user-invalid, успіх через :target;
- Hover і focus-visible картки роботи, fixed header, кнопка «вгору» через якір;
- Доступність: видимий фокус, aria-label для іконок, label для полів, aria-describedby для помилки
- Використання сервісу **https://squoosh.app/** для переформатування зображень з макету keepsake з растрового формату png, з якого  я копіював всі зображення, в WebP, адже не зумів це виконати безпосередньо в середовищі Figma

## Структура

index.html, css/reset.css, css/style.css, images.
