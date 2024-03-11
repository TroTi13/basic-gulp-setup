# Simple Gulp setup to handle most creative front-end projects

## Features
- [x] Sass to CSS
- [x] Webpack to bundle JS
- [x] BrowserSync to live reload
- [x] Image optimization
- [x] Fonts & media copy

## Getting Started
1. Clone this repository
2. Run `npm start`
3. Start coding
4. To build your project run `npm run build`

## Folder Structure
```
.
├── src
│   ├── all components and source files here
├── public
│   ├── resources
│   │   ├── compiled files in subfolders
│   ├── index.html
├── gulpfile.js
├── package.json
└── README.md
```

## Configuration
- `gulpfile.js` contains all the tasks for automation
- `package.json` contains all the dependencies and the eslint configuration

In `gulpfile.js` you can change the configuration of the tasks, like the source and destination folders, in the `CONFIG` object.
Switch between `baseDir` and `url` to use a local server or a proxy server (if you have a local domain serving php for instance).