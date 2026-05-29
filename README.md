# In Style Studio — GitHub Pages Site

## 🚀 Как задеплоить на GitHub Pages (URL: xoxo.github.io)

### Вариант 1: URL будет `xoxo.github.io` (root, без подпапки)

1. Создай репозиторий с точным именем: **`xoxo.github.io`**
2. Загрузи `index.html` в корень репозитория
3. Зайди в Settings → Pages → Source: `main` branch, папка `/ (root)`
4. Сайт будет доступен по `https://xoxo.github.io`

### Вариант 2: URL будет `xoxo.github.io/instyle` (подпапка)

1. Создай любой репозиторий, например: **`instyle`**
2. Загрузи `index.html` в корень
3. Зайди в Settings → Pages → Source: `main`, `/ (root)`
4. Сайт: `https://xoxo.github.io/instyle`

---

## 📁 Файлы для загрузки

- `index.html` — весь сайт (один файл, никаких зависимостей)

## ✅ Что уже работает

- Полная копия дизайна: hero, why, services, gallery, reviews, booking, footer
- Плавная навигация по якорям
- Мобильное меню
- Анимации при скролле
- Форма записи с валидацией
- Карта Google (embedded)
- Адаптивная вёрстка (mobile-first)
- Русскоязычный контент 1:1

## 📝 Доп. настройка

Если хочешь реально принимать заявки из формы:
- Зарегистрируйся на [formspree.io](https://formspree.io)
- Получи свой endpoint вида `https://formspree.io/f/XXXXXX`
- В `index.html` найди функцию `submitForm()` и добавь `fetch` к этому URL
