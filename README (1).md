# Astra Smart Hub

A modern, human-centered smart home dashboard built with React, TypeScript, Vite, Tailwind CSS, and shadcn/ui.

## Features
- Real-time device overview and quick controls
- Rooms, automations, and energy insights
- Secure auth flow (demo)
- Responsive UI with elegant animations

## Getting Started
```sh
# 1) Install dependencies
npm install

# 2) Start dev server
npm run dev

# 3) Build for production
npm run build

# 4) Preview production build
npm run preview
```

## Scripts
- `npm run dev`: Start Vite dev server
- `npm run build`: Build the app
- `npm run preview`: Preview the production build
- `npm run lint`: Run ESLint

## Tech Stack
- React 18 + TypeScript
- Vite
- Tailwind CSS + `tailwindcss-animate`
- shadcn/ui (Radix UI primitives)
- React Router
- Lucide icons

## Project Structure
```text
src/
  components/
    ui/            # shadcn/ui components
    DeviceCard.tsx
    DashboardLayout.tsx
  pages/           # Route pages (Dashboard, Devices, Automation, ...)
  hooks/
  lib/
  App.tsx
  main.tsx
public/
  favicon.ico
  placeholder.svg  # Social share image
```

## Configuration
- Update site meta in `index.html` (title, description, social image).
- Place social share image(s) in `public/` and reference them as `/your-image.png`.
- Favicon is served from `public/favicon.ico`.

## Deployment
Any static hosting that serves the `dist/` directory works:
- Vercel, Netlify, Cloudflare Pages, GitHub Pages, etc.

Typical steps:
```sh
npm run build
# deploy the dist/ folder with your preferred provider
```

## Contributing
- Use meaningful commit messages
- Keep components small and composable
- Run `npm run lint` before submitting changes

## License
This project is provided as-is for demonstration purposes. Update with your preferred license if needed.
