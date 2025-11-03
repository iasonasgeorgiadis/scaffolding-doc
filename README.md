# Scaffolding Doc for Modern Frameworks

A comprehensive reference guide for framework scaffolding tools and their official documentation.

---

## Frontend Frameworks & Scaffolding

### React
- **Create React App**: https://create-react-app.dev/
- **Vite (React template)**: https://vitejs.dev/guide/#scaffolding-your-first-vite-project
  - Command: `npm create vite@latest my-app -- --template react`
  - React + TypeScript: `npm create vite@latest my-app -- --template react-ts`

### Vue.js
- **Vue CLI**: https://cli.vuejs.org/
- **Vite (Vue template)**: `npm create vite@latest my-app -- --template vue`
- **create-vue**: https://github.com/vuejs/create-vue

### Angular
- **Angular CLI**: https://angular.io/cli

### Svelte
- **SvelteKit**: https://kit.svelte.dev/
- **Vite (Svelte template)**: `npm create vite@latest my-app -- --template svelte`

### Solid.js
- **Official templates**: https://www.solidjs.com/guides/getting-started
- **Vite (Solid template)**: `npm create vite@latest my-app -- --template solid`

### Preact
- **preact-cli**: https://preactjs.com/cli/
- **Vite (Preact template)**: `npm create vite@latest my-app -- --template preact`

### Lit
- **Starter kits**: https://lit.dev/docs/tools/starter-kits/
- **Vite (Lit template)**: `npm create vite@latest my-app -- --template lit`

### Vanilla JavaScript/TypeScript
- **Vite**: `npm create vite@latest my-app -- --template vanilla`
- **Vite + TypeScript**: `npm create vite@latest my-app -- --template vanilla-ts`

---

## Full-Stack/Meta Frameworks

### Next.js (React)
- **create-next-app**: https://nextjs.org/docs/getting-started/installation
- Command: `npx create-next-app@latest`

### Nuxt (Vue)
- **Documentation**: https://nuxt.com/docs/getting-started/installation
- Command: `npx nuxi init my-app`

### Remix (React)
- **create-remix**: https://remix.run/docs/en/main/start/quickstart
- Command: `npx create-remix@latest`

### Astro (Multi-framework)
- **Documentation**: https://astro.build/
- Command: `npm create astro@latest`
- Supports: React, Vue, Svelte, Solid, Preact, Lit

### SvelteKit (Svelte)
- **Documentation**: https://kit.svelte.dev/
- Command: `npm create svelte@latest`

### Qwik / Qwik City
- **Documentation**: https://qwik.builder.io/docs/getting-started/
- Command: `npm create qwik@latest`

### Analog (Angular)
- **Documentation**: https://analogjs.org/docs/getting-started
- Command: `npm create analog@latest`

### SolidStart (Solid.js)
- **Documentation**: https://start.solidjs.com/getting-started/what-is-solidstart
- Command: `npm create solid@latest`

---

## Backend Frameworks

### Express.js (Node.js)
- **express-generator**: https://expressjs.com/en/starter/generator.html
- Command: `npx express-generator`

### NestJS (Node.js/TypeScript)
- **Documentation**: https://docs.nestjs.com/cli/overview
- Command: `npm i -g @nestjs/cli && nest new project-name`

### Fastify (Node.js)
- **fastify-cli**: https://github.com/fastify/fastify-cli
- Command: `npm install --global fastify-cli && fastify generate myapp`

### Koa (Node.js)
- **koa-generator**: https://github.com/17koa/koa-generator

### Adonis.js (Node.js/TypeScript)
- **Documentation**: https://docs.adonisjs.com/guides/getting-started/installation
- Command: `npm init adonisjs@latest`

### Hono (Edge/Node.js)
- **Documentation**: https://hono.dev/getting-started/basic
- Command: `npm create hono@latest`

### tRPC (TypeScript RPC)
- **Documentation**: https://trpc.io/docs/quickstart
- Command: `npm create t3-app@latest` (with Next.js)

### Elysia (Bun)
- **Documentation**: https://elysiajs.com/quick-start.html
- Command: `bun create elysia my-app`

---

## Python

### Django
- **Documentation**: https://docs.djangoproject.com/en/stable/intro/tutorial01/
- Command: `django-admin startproject myproject`

### FastAPI
- **Documentation**: https://fastapi.tiangolo.com/tutorial/
- Command: `pip install fastapi[all]` (no official scaffolder, cookiecutters available)

### Flask
- **Documentation**: https://flask.palletsprojects.com/en/stable/cli/
- Command: `flask create my-app` (Flask 2.2+)

### Litestar (formerly Starlite)
- **Documentation**: https://docs.litestar.dev/latest/
- Command: `pip install litestar[cli] && litestar init`

---

## Ruby

### Ruby on Rails
- **Documentation**: https://guides.rubyonrails.org/getting_started.html
- Command: `rails new myapp`

---

## PHP

### Laravel
- **Documentation**: https://laravel.com/docs/installation
- Command: `composer create-project laravel/laravel myapp`

### Symfony
- **Documentation**: https://symfony.com/doc/current/setup.html
- Command: `symfony new my_project_name`

---

## Mobile

### React Native
- **React Native CLI**: https://reactnative.dev/docs/environment-setup
- Command: `npx react-native init MyApp`

### Expo (React Native)
- **Documentation**: https://docs.expo.dev/get-started/create-a-project/
- Command: `npx create-expo-app@latest`

### Flutter
- **Documentation**: https://docs.flutter.dev/get-started/install
- Command: `flutter create myapp`

### Ionic
- **Documentation**: https://ionicframework.com/docs/cli
- Command: `npm install -g @ionic/cli && ionic start`
- Supports: React, Vue, Angular

### Tauri (Desktop/Mobile with web tech)
- **Documentation**: https://tauri.app/v1/guides/getting-started/setup/
- Command: `npm create tauri-app@latest`

---

## Build Tools/Universal

### Vite
- **Documentation**: https://vitejs.dev/guide/
- Command: `npm create vite@latest`
- **Templates**: vanilla, vanilla-ts, react, react-ts, vue, vue-ts, preact, preact-ts, lit, lit-ts, svelte, svelte-ts, solid, solid-ts

### Turbo (Monorepo)
- **Documentation**: https://turbo.build/repo/docs/getting-started/create-new
- Command: `npx create-turbo@latest`

### Nx (Monorepo)
- **Documentation**: https://nx.dev/getting-started/intro
- Command: `npx create-nx-workspace@latest`

### Parcel
- **Documentation**: https://parceljs.org/getting-started/webapp/
- No official scaffolder (zero-config bundler)

### Webpack
- **Documentation**: https://webpack.js.org/guides/getting-started/
- No official scaffolder (manual setup or framework-specific)

---

## Full-Stack Starter Kits

### T3 Stack (Next.js + tRPC + Tailwind + Prisma)
- **Documentation**: https://create.t3.gg/
- Command: `npm create t3-app@latest`

### RedwoodJS (React + GraphQL)
- **Documentation**: https://redwoodjs.com/docs/quick-start
- Command: `yarn create redwood-app my-app`

### Blitz.js (Next.js based)
- **Documentation**: https://blitzjs.com/docs/get-started
- Command: `npm install -g blitz && blitz new myApp`

### Wasp (React + Node.js DSL)
- **Documentation**: https://wasp-lang.dev/docs
- Command: `curl -sSL https://get.wasp-lang.dev/installer.sh | sh`

---

## Desktop

### Electron
- **Documentation**: https://www.electronjs.org/docs/latest/tutorial/quick-start
- Various boilerplates: electron-forge, electron-builder

### Tauri
- **Documentation**: https://tauri.app/
- Command: `npm create tauri-app@latest`

---

## Notes

- Most modern frameworks support TypeScript variants
- Vite is becoming the standard build tool for many frameworks
- Many frameworks offer interactive CLI prompts for additional configuration
- Check official documentation for the latest installation methods and options

---

**Last Updated**: November 2025