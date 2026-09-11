# WomenFitness — лендинг міні-курсу

Статичний односторінковий сайт для міні-курсу WomenFitness.

## Сторінки
- `/` — основний лендінг (8 уроків)
- `/kontakt-z-tilom` — нова версія лендінга (4 уроки, Aurora Silk)
- `/design/a|b|c` — три напрямки редизайну (noindex, тільки для порівняння)

## Стек
- Чистий HTML/CSS/JS, без фреймворків
- Шрифти: Jost + Cormorant Garamond (Google Fonts)
- Зображення: AVIF + JPG через `<picture>`
- Відео: нативні `<video>` з ліниво підвантажуваним `src` через IntersectionObserver
- Медіа спільні для обох сторінок: `images/`, `videos/`

## Локальний запуск
```bash
python3 -m http.server 4173
# або
npx serve .
```

## Деплой
Vercel:
```bash
vercel --prod
```
