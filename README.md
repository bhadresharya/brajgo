# Braj Go Tour and Travels

Static website for **Braj Go Tour and Travels** – tours and taxi in Mathura, Vrindavan & Agra. Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## Setup

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Commands

| Command           | Action                          |
| ----------------- | ------------------------------- |
| `npm run dev`     | Start dev server                |
| `npm run build`   | Build for production to `dist/` |
| `npm run preview` | Preview production build        |

## Adding images

- **Hero banner:** Add `public/images/hero-banner.jpg` and the Hero section will use it (update `Hero.astro` to use `<img src="/images/hero-banner.jpg" ... />`).
- **Destination cards:** Add images to `public/images/` and reference them in `Destinations.astro` and `OtherDestinations.astro`.

## Contact (from site)

- Mobile: 9228597072, 9413211264  
- WhatsApp: 9312301972, 9433211264  
- Update full address in `src/components/Contact.astro` when ready.
