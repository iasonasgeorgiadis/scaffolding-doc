# Scaffolding Doc for Modern Frameworks

A comprehensive reference guide for framework scaffolding tools and their official documentation.

## Frontend Frameworks & Scaffolding

### React
- **Create React App**: https://create-react-app.dev/
  ```bash
  npx create-react-app my-app
  ```

- **Vite (React template)**: https://vitejs.dev/guide/#scaffolding-your-first-vite-project
  ```bash
  npm create vite@latest my-app -- --template react
  ```

- **Vite + React + TypeScript**:
  ```bash
  npm create vite@latest my-app -- --template react-ts
  ```

### Vue.js
- **Vue CLI**: https://cli.vuejs.org/
  ```bash
  npm install -g @vue/cli
  vue create my-app
  ```

- **Vite (Vue template)**:
  ```bash
  npm create vite@latest my-app -- --template vue
  ```

- **create-vue**: https://github.com/vuejs/create-vue
  ```bash
  npm create vue@latest
  ```

### Angular
- **Angular CLI**: https://angular.io/cli
  ```bash
  npm install -g @angular/cli
  ng new my-app
  ```

### Svelte
- **SvelteKit**: https://kit.svelte.dev/
  ```bash
  npm create svelte@latest my-app
  ```

- **Vite (Svelte template)**:
  ```bash
  npm create vite@latest my-app -- --template svelte
  ```

### Solid.js
- **Official templates**: https://www.solidjs.com/guides/getting-started
  ```bash
  npx degit solidjs/templates/js my-app
  ```

- **Vite (Solid template)**:
  ```bash
  npm create vite@latest my-app -- --template solid
  ```

### Preact
- **preact-cli**: https://preactjs.com/cli/
  ```bash
  npx preact-cli create default my-app
  ```

- **Vite (Preact template)**:
  ```bash
  npm create vite@latest my-app -- --template preact
  ```

### Lit
- **Starter kits**: https://lit.dev/docs/tools/starter-kits/
  ```bash
  npm init @open-wc
  ```

- **Vite (Lit template)**:
  ```bash
  npm create vite@latest my-app -- --template lit
  ```

### Vanilla JavaScript/TypeScript
- **Vite (Vanilla JS)**:
  ```bash
  npm create vite@latest my-app -- --template vanilla
  ```

- **Vite + TypeScript**:
  ```bash
  npm create vite@latest my-app -- --template vanilla-ts
  ```

## Full-Stack/Meta Frameworks

### Next.js (React)
- **create-next-app**: https://nextjs.org/docs/getting-started/installation
  ```bash
  npx create-next-app@latest my-app
  ```

### Nuxt (Vue)
- **Documentation**: https://nuxt.com/docs/getting-started/installation
  ```bash
  npx nuxi init my-app
  ```

### Remix (React)
- **create-remix**: https://remix.run/docs/en/main/start/quickstart
  ```bash
  npx create-remix@latest my-app
  ```

### Astro (Multi-framework)
- **Documentation**: https://astro.build/
  ```bash
  npm create astro@latest my-app
  ```
  - Supports: React, Vue, Svelte, Solid, Preact, Lit

### SvelteKit (Svelte)
- **Documentation**: https://kit.svelte.dev/
  ```bash
  npm create svelte@latest my-app
  ```

### Qwik / Qwik City
- **Documentation**: https://qwik.builder.io/docs/getting-started/
  ```bash
  npm create qwik@latest
  ```

### Analog (Angular)
- **Documentation**: https://analogjs.org/docs/getting-started
  ```bash
  npm create analog@latest
  ```

### SolidStart (Solid.js)
- **Documentation**: https://start.solidjs.com/getting-started/what-is-solidstart
  ```bash
  npm create solid@latest
  ```

## Backend Frameworks

### Express.js (Node.js)
- **express-generator**: https://expressjs.com/en/starter/generator.html
  ```bash
  npx express-generator my-app
  ```

### NestJS (Node.js/TypeScript)
- **Documentation**: https://docs.nestjs.com/cli/overview
  ```bash
  npm i -g @nestjs/cli
  nest new project-name
  ```

### Fastify (Node.js)
- **fastify-cli**: https://github.com/fastify/fastify-cli
  ```bash
  npm install --global fastify-cli
  fastify generate myapp
  ```

### Koa (Node.js)
- **koa-generator**: https://github.com/17koa/koa-generator
  ```bash
  npx koa-generator my-app
  ```

### Adonis.js (Node.js/TypeScript)
- **Documentation**: https://docs.adonisjs.com/guides/getting-started/installation
  ```bash
  npm init adonisjs@latest my-app
  ```

### Hono (Edge/Node.js)
- **Documentation**: https://hono.dev/getting-started/basic
  ```bash
  npm create hono@latest my-app
  ```

### tRPC (TypeScript RPC)
- **Documentation**: https://trpc.io/docs/quickstart
  ```bash
  npm create t3-app@latest
  ```
  - Includes Next.js + tRPC + Tailwind + Prisma

### Elysia (Bun)
- **Documentation**: https://elysiajs.com/quick-start.html
  ```bash
  bun create elysia my-app
  ```

## Python

### Django
- **Documentation**: https://docs.djangoproject.com/en/stable/intro/tutorial01/
  ```bash
  pip install django
  django-admin startproject myproject
  ```

### FastAPI
- **Documentation**: https://fastapi.tiangolo.com/tutorial/
  ```bash
  pip install fastapi[all]
  ```
  - No official scaffolder (cookiecutters available)

### Flask
- **Documentation**: https://flask.palletsprojects.com/en/stable/cli/
  ```bash
  pip install flask
  flask --app my-app init
  ```

### Litestar (formerly Starlite)
- **Documentation**: https://docs.litestar.dev/latest/
  ```bash
  pip install litestar[cli]
  litestar init
  ```

## Ruby

### Ruby on Rails
- **Documentation**: https://guides.rubyonrails.org/getting_started.html
  ```bash
  gem install rails
  rails new myapp
  ```

## PHP

### Laravel
- **Documentation**: https://laravel.com/docs/installation
  ```bash
  composer create-project laravel/laravel myapp
  ```

### Symfony
- **Documentation**: https://symfony.com/doc/current/setup.html
  ```bash
  symfony new my_project_name
  ```

## Mobile

### React Native
- **React Native CLI**: https://reactnative.dev/docs/environment-setup
  ```bash
  npx react-native init MyApp
  ```

### Expo (React Native)
- **Documentation**: https://docs.expo.dev/get-started/create-a-project/
  ```bash
  npx create-expo-app@latest my-app
  ```

### Flutter
- **Documentation**: https://docs.flutter.dev/get-started/install
  ```bash
  flutter create myapp
  ```

### Ionic
- **Documentation**: https://ionicframework.com/docs/cli
  ```bash
  npm install -g @ionic/cli
  ionic start my-app
  ```
  - Supports: React, Vue, Angular

### Tauri (Desktop/Mobile with web tech)
- **Documentation**: https://tauri.app/v1/guides/getting-started/setup/
  ```bash
  npm create tauri-app@latest
  ```

## Build Tools & Universal

### Vite
- **Documentation**: https://vitejs.dev/guide/
  ```bash
  npm create vite@latest
  ```
  - **Templates**: vanilla, vanilla-ts, react, react-ts, vue, vue-ts, preact, preact-ts, lit, lit-ts, svelte, svelte-ts, solid, solid-ts

### Turbo (Monorepo)
- **Documentation**: https://turbo.build/repo/docs/getting-started/create-new
  ```bash
  npx create-turbo@latest
  ```

### Nx (Monorepo)
- **Documentation**: https://nx.dev/getting-started/intro
  ```bash
  npx create-nx-workspace@latest
  ```

### Parcel
- **Documentation**: https://parceljs.org/getting-started/webapp/
  - No official scaffolder (zero-config bundler)

### Webpack
- **Documentation**: https://webpack.js.org/guides/getting-started/
  - No official scaffolder (manual setup or framework-specific)

## Full-Stack Starter Kits

### T3 Stack (Next.js + tRPC + Tailwind + Prisma)
- **Documentation**: https://create.t3.gg/
  ```bash
  npm create t3-app@latest
  ```

### RedwoodJS (React + GraphQL)
- **Documentation**: https://redwoodjs.com/docs/quick-start
  ```bash
  yarn create redwood-app my-app
  ```

### Blitz.js (Next.js based)
- **Documentation**: https://blitzjs.com/docs/get-started
  ```bash
  npm install -g blitz
  blitz new myApp
  ```

### Wasp (React + Node.js DSL)
- **Documentation**: https://wasp-lang.dev/docs
  ```bash
  curl -sSL https://get.wasp-lang.dev/installer.sh | sh
  wasp new my-app
  ```

## Desktop

### Electron
- **Documentation**: https://www.electronjs.org/docs/latest/tutorial/quick-start
  ```bash
  npm install --save-dev electron
  ```
  - Various boilerplates available:
    - **electron-forge**:
      ```bash
      npm init electron-app@latest my-app
      ```
    - **electron-react-boilerplate**:
      ```bash
      git clone --depth 1 --branch main https://github.com/electron-react-boilerplate/electron-react-boilerplate.git my-app
      ```

### Tauri
- **Documentation**: https://tauri.app/
  ```bash
  npm create tauri-app@latest
  ```

## Notes

- Most modern frameworks support TypeScript variants
- Vite is becoming the standard build tool for many frameworks
- Many frameworks offer interactive CLI prompts for additional configuration
- Check official documentation for the latest installation methods and options

**Last Updated**: November 2025