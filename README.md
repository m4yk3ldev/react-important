# React Libraries 2023
[Twitch Midudev](https://www.twitch.tv/videos/1750792562)
## Crear proyecto

Client Side: Vite
SSR: Next.js
Static: Astro

## Package Manager

Por defecto: npm
Por cambiar o por probar: pnpm

## State Management

- Cosas estáticas o que cambian poco: React Context
- Para estado global general: Zustand
- Redux Toolkit SÓLO para proyectos medio/grandecitos con estados globales complejos
- Para proyectos GRANDES, evitar el estado global y depender de React Query, Apollo, Flux...

## Data Fetching

Tanstack Query/SWR
urlQL

## Routing

- NextJS File System Routing
- React Router (para proyectos con paths complejos o muchas páginass)
- Wouter (smaller alternative, páginas sencillas)

## CSS Styling

- TailwindCSS
- CSS Modules
- Vanilla Extract

## React UI Libraries

- Framer Motion
- Auto Animate

## Charts

- Recharts

## Forms

- https://react-hook-form.com/
- zod (para validaciones)

# Autenticación

- Supabase Auth
- Next Auth
- O probar Lucia Auth/Authjs.dev

# Hosting

Proyectos web:
1. Vercel
2. Netlify

Proyectos web + Workers (Edge Functions):
Especial mención: Cloudflare

Dockerfiles:
1. Railway
2. Fly.io
3. Render

# Testing

Vitest + Playwright + React Testing Library

# Time in React

Menos momento lo que quieras.

1. date-fns
2. dayjs
3. luxon