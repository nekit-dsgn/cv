# cv
This section will contain information about me, my skills, my experience, and so on. 
# CV — Nikita Barabash

Онлайн-резюме Никиты Барабаша, Middle Product Designer. Статический одностраничный сайт, размещённый на GitHub Pages.

**Live:** https://nekit-dsgn.github.io/cv/

## Что внутри

- `index.html` — всё резюме: разметка, стили и контент в одном файле. Без сборки, без зависимостей.

## Локальный просмотр

Просто открой `index.html` в браузере двойным кликом. Либо подними локальный сервер:

```bash
python -m http.server 8000
```

и открой http://localhost:8000.

## Как обновить резюме

1. Отредактируй нужные секции в `index.html` (опыт, навыки, контакты).
2. Закоммить изменения и запушь:
   ```bash
   git add index.html
   git commit -m "Update CV"
   git push
   ```
3. GitHub Pages автоматически пересоберёт сайт через ~1 минуту.

## Публикация на GitHub Pages

Один раз:

1. Создай публичный репозиторий (например, `cv`) и запушь туда содержимое папки.
2. В репозитории: **Settings → Pages → Source: Deploy from branch → Branch: `main` / `/ (root)` → Save**.
3. Сайт будет доступен по адресу `https://nekit-dsgn.github.io/cv/`.

## Стек

- Чистый HTML + CSS
- Шрифт [Inter](https://fonts.google.com/specimen/Inter) через Google Fonts
- Адаптивная вёрстка (breakpoints: 768px, 480px)

## Контакты

- Email: ex.nekittt@gmail.com
- Портфолио: https://nekit-dsgn.figma.site
- Dribbble: https://dribbble.com/ex_nekittt
- Behance: https://behance.net/nekitt
