# Lucy Epoxy Studio

Elegancka, minimalistyczna strona firmowa w Astro przygotowana pod rynek **PL / DE / EN**, z naciskiem na konwersję zapytań ofertowych.

## Domena i kontakt

- Domena produkcyjna: **https://lucyepoxy.com**
- E-mail kontaktowy: **info@lucyepoxy.com**

## Stack

- Astro 4
- TypeScript
- CSS (bez przeładowania efektami)
- Wielojęzyczność: PL / DE / EN

## Uruchomienie

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy (Vercel)

Projekt zawiera `vercel.json` i jest gotowy do podpięcia repo na Vercel.

## Szkielet projektu

```text
lucy-epoxy-studio/
├── public/
│   ├── image/                       # miejsce na nowe zdjęcia od klienta
│   ├── images/                      # aktualnie używane obrazy strony
│   │   └── projects/
│   └── downloads/
│       └── lucy-epoxy-studio.apk
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── HeroSection.astro
│   │   ├── FeaturesSection.astro
│   │   ├── ProjectsSection.astro
│   │   ├── AboutSection.astro
│   │   └── CTASection.astro
│   ├── layouts/
│   │   └── MainLayout.astro
│   └── pages/
│       ├── index.astro
│       ├── pl/
│       │   ├── realizacje.astro
│       │   ├── kontakt.astro
│       │   └── aplikacja.astro
│       ├── de/
│       │   ├── index.astro
│       │   ├── realisierungen.astro
│       │   ├── kontakt.astro
│       │   └── android-app.astro
│       └── en/
│           ├── index.astro
│           ├── projects.astro
│           ├── contact.astro
│           └── mobile-app.astro
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── tailwind.config.mjs
└── vercel.json
```

## SEO i market fit

- **PL**: treści i CTA pod polskiego klienta.
- **DE**: osobne komunikaty pod rynek niemiecki (priorytet).
- **EN**: komunikacja dla krajów UE.
- Canonical + hreflang + Open Graph ustawione w layoucie.