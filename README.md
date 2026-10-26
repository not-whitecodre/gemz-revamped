# Gemz Software

The marketing website for Gemz Software, built with Next.js and TypeScript. It
features the Gemz brand design system, responsive landing-page sections, and a
component showcase at `/design-system`.

## Requirements

- Node.js supported by the installed Next.js version
- npm

## Getting started

Install dependencies and start the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the site.

## Available commands

```bash
npm run dev      # Start the local development server
npm run lint     # Run ESLint
npx tsc --noEmit # Check TypeScript types
npm run build    # Create a production build
npm run start    # Serve the production build
```

## Project structure

- `src/app/` — App Router pages, layouts, global styles, and metadata routes
- `src/components/sections/` — Landing-page sections
- `src/components/ui/` — Reusable interface components
- `src/lib/` — Shared site data, utilities, and motion presets
- `docs/design-system/colors.md` — Brand palette and visual direction

The root page is composed in `src/app/page.tsx`. Shared design-system components
can be previewed at `/design-system`.
