# Astro-лендинг «Бизнес центр Trilliant»

Это адаптивный Astro-проект для StackBlitz. В проекте уже заменены основные тексты на:

- название: **Бизнес центр Trilliant**
- адрес: **улица Шахрисабз, 2**
- мобильная версия: включена в `src/styles/global.css`
- мобильное меню: находится в `src/components/Header.astro`

Код не копирует Tilda-верстку и не содержит чужие изображения. Фото, реальные площади, телефон, email и PDF нужно заменить на свои.

## Как запустить в StackBlitz

1. Откройте новый Astro-проект через astro.new.
2. Распакуйте этот архив.
3. Перетащите в StackBlitz содержимое папки проекта, а не саму папку целиком:
   - `package.json`
   - `astro.config.mjs`
   - `tsconfig.json`
   - `src`
   - `public`
4. В терминале выполните:

```bash
npm install
npm run dev
```

## Где редактировать информацию

- `src/data/offices.ts` — офисы, площади, этажи, планировки
- `src/data/tenants.ts` — арендаторы/резиденты
- `src/data/navigation.ts` — меню
- `src/components/Hero.astro` — первый экран
- `src/components/Stats.astro` — блок «О бизнес-центре»
- `src/components/Location.astro` — адрес и карта
- `src/components/Contact.astro` — контакты и форма
- `src/styles/global.css` — дизайн и мобильная версия

## Фото

Положите изображения в:

```txt
public/images/
```

И используйте их так:

```astro
<img src="/images/photo.webp" alt="Бизнес центр Trilliant" />
```

Лучше использовать WebP/AVIF, чтобы сайт быстрее загружался.
