yarn

# Vite + React Modern Starter

A fast, opinionated template for building single-page applications with Vite, React, and a powerful modern stack.

## Features

- ⚡ Vite for instant dev server and optimized builds
- ⚛️ React 19 for UI development
- 🗂️ File-based routing (see `src/config/dynamicRouter.tsx`)
- 🪝 Zustand for state management
- 🧩 Zod for schema validation
- 🔗 TanStack Query for data fetching and caching
- 🎬 GSAP for advanced animations
- 🌐 i18next for internationalization
- 🛠️ Tailwind CSS for utility-first styling

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn
   # or
   pnpm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

## Scripts

- `dev` — Start Vite dev server
- `build` — Build for production
- `preview` — Preview production build locally
- `lint` — Run ESLint

## Project Structure

```
src/
  components/      # React components
  config/          # App configuration (routing, i18n, GSAP plugins)
  hooks/           # Custom React hooks
  languages/       # i18n language files
  pages/           # Route pages (file-based routing)
  services/        # API and utilities
  main.tsx         # App entry point
  global.css       # Global styles
index.html
vite.config.ts
package.json
```

## Routing

- File-based routing is handled via `src/config/dynamicRouter.tsx`.
- Pages are defined in `src/pages/` as `page.tsx` files.
- Layouts are supported via `layout.tsx` files.

## Environment

- Use `.env.local`, `.env.development`, and `.env.production` for environment variables.
- Prefix client-exposed variables with `VITE_`.

## Deployment

Build and deploy the `dist` directory to any static host:

```bash
npm run build
# then upload ./dist to your host
```

## Customization

- Swap styling solutions as needed.
- Add or remove libraries to fit your workflow.

## License

MIT (or add your own license file).
