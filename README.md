# vue-admin-template-sentry

[Documentation](https://juejin.im/post/5ea98032e51d454da7416f19)

English | [简体中文](./README-zh.md)

> A minimal vue admin template with Element UI & axios & iconfont & permission control & lint

**Live demo:** https://mokedeng.github.io/vue-admin-template-sentry/

## Quick Start Guide

### Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (>= 8.9) - [Download here](https://nodejs.org/)
- **npm** (>= 3.0.0) - Comes with Node.js
- **Git** - [Download here](https://git-scm.com/)

### Installation & Setup

Follow these simple steps to get the project running locally:

#### 1. Clone the Repository
```bash
git clone https://github.com/mokedeng/vue-admin-template-sentry.git
cd vue-admin-template-sentry
```

#### 2. Install Dependencies
```bash
npm install
```

#### 3. Start Development Server
```bash
npm run dev
```

The application will automatically open in your browser at `http://localhost:9528`

#### 4. Login Credentials
Use the following default credentials to access the admin panel:
- **Username:** admin
- **Password:** any password (mock authentication)

### Project Structure Overview

```
src/
├── api/          # API request functions
├── assets/       # Static assets (images, etc.)
├── components/   # Reusable Vue components
├── layout/       # Layout components (sidebar, navbar, etc.)
├── router/       # Vue Router configuration
├── store/        # Vuex store modules
├── styles/       # Global styles and SCSS files
├── utils/        # Utility functions
└── views/        # Page components
```

### What's Next?

- Explore the **Dashboard** to see the admin interface
- Check out the **Table** and **Form** examples
- Customize the layout and styling to match your needs
- Add your own API endpoints in the `src/api/` directory

## Build Setup

```bash
# clone the project
git clone https://github.com/mokedeng/vue-admin-template-sentry.git

# enter the project directory
cd vue-admin-template-sentry

# install dependency
npm install

# develop
npm run dev
```

This will automatically open http://localhost:9528

## Build

```bash
# build for test environment
npm run build:stage

# build for production environment
npm run build:prod
```

## Advanced

```bash
# preview the release environment effect
npm run preview

# preview the release environment effect + static resource analysis
npm run preview -- --report

# code format check
npm run lint

# code format check and auto fix
npm run lint -- --fix
```

Refer to [Documentation](https://panjiachen.github.io/vue-element-admin-site/guide/essentials/deploy.html) for more information

## Demo

![demo](https://github.com/PanJiaChen/PanJiaChen.github.io/blob/master/images/demo.gif)


## Related Project

- [vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)

- [electron-vue-admin](https://github.com/PanJiaChen/electron-vue-admin)

- [vue-typescript-admin-template](https://github.com/Armour/vue-typescript-admin-template)

- [awesome-project](https://github.com/PanJiaChen/vue-element-admin/issues/2312)

## Browsers support

Modern browsers and Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| --------- | --------- | --------- | --------- |
| IE10, IE11, Edge| last 2 versions| last 2 versions| last 2 versions