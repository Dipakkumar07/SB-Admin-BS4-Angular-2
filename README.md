# Introduction

Simple Dashboard Admin App built using Angular 2 and Bootstrap 4

It is something similar to the Angular Quick Start but does the entire build with gulp.

`SB Admin BS 4 Angular2` provides the following features:

- Ready to go, statically typed build system using gulp for working with TypeScript.
- Production and development builds.
- Sample unit tests with Jasmine and Karma.
- End-to-end tests with Protractor.
- Development server with Livereload.
- Experimental hot loading support.
- Following the best practices for your application’s structure.
- Manager of your type definitions using [typings](https://github.com/typings/typings).
- Basic Service Worker, which implements "Cache then network strategy".

# How to start

**Note** that this seed project requires node v4.x.x or higher and npm 2.14.7.

You must have `ts-node` installed as global. If you don't, use:

```bash
npm install -g ts-node
```

In order to start the seed use:


```bash
git clone git@github.com:start-angular/SB-Admin-BS4-Angular-2.git
cd SB-Admin-BS4-Angular-2
# install the project's dependencies
npm install
# watches your files and uses livereload by default
npm start

```

# Configuration

Default application server configuration

```javascript
var PORT             = 8080;
var LIVE_RELOAD_PORT = 4002;
var APP_BASE         = '/';
```

# Directory Structure

```
.
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── app
│   ├── layout
│   │   └── components
│   │       ├── app.css
│   │       ├── app.e2e.ts
│   │       ├── app.html
│   │       ├── app.ts
│   │       └── app.spec.ts
│   ├── assets
│   │   ├── img
│   │   │   └── smile.png
│   │   ├── bootstarp
│   │   ├── fontawesome-4.5.0
│   │   └── main.css
│   ├── pages
│   │   └── components
│   │       ├── blank-page
│   │       ├── bootstrap-element
│   │       ├── charts
│   │       ├── components
│   │       └── form
│   │       └── grid
│   │       └── home
│   │       └── tables
│   ├── shared
│   │   └── services
│   │       ├── name_list.ts
│   │       └── name_list.spec.ts
│   ├── hot_loader_main.ts
│   ├── main.ts
│   └── index.html
├── dist
├── test
├── tools
│   ├── manual_typings
│   ├── tasks
│   ├── utils
│   ├── config.ts
│   └── utils.ts
├── appveyor.yml
├── gulpfile.ts
├── karma.conf.js
├── package.json
├── protractor.conf.js
├── test-main.js
├── tsconfig.json
├── tslint.json
└── typings.json
```

# Change Log

Powered by [StartAngular](http://startangular.com/) & [StrapUI](http://strapui.com/)