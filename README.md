# Astro Starter

Starter projektu na Astro + pnpm.

## Start

```sh
pnpm install
pnpm dev
```

Strona działa pod `http://localhost:4321`.

## Komendy

| Komenda        | Co robi                                    |
| :------------- | :----------------------------------------- |
| `pnpm install` | Instaluje zależności z `pnpm-lock.yaml`    |
| `pnpm dev`     | Serwer deweloperski (`localhost:4321`)     |
| `pnpm host`    | Serwer deweloperski dostępny w sieci (LAN) |
| `pnpm build`   | Build produkcyjny do `./dist/`             |
| `pnpm preview` | Podgląd buildu lokalnie                    |
| `pnpm check`   | Sprawdzenie typów (`astro check`)          |
| `pnpm format`  | Formatowanie Prettierem                    |

## Struktura

```text
/
├── public/
├── src/
│   ├── components/
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Section.astro
│   │   ├── SectionHeader.astro
│   │   ├── Seo.astro
│   │   └── ServiceCard.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
└── package.json
```

## Nowy projekt z tego startera

W `astro.config.mjs` podmień `site` na prawdziwą domenę (z niej liczy się `canonical` i `og:url` w `Seo.astro`).
