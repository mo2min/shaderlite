# electron-vue-example

# Making vue app electronable

### Adding bootstrap

- npm i bootstrap-vue -s 
- add bootstrap scripts to app.js
```
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
```

### changes to background.js

- Add window.maximize()
- Changing icon for serve in background.js main window BrowserWindow config `icon:  'assets/logo.png'`

### Adding sqlite3
```
npm install --save-dev electron-builder
npm install --save sqlite3
npm run postinstall
```
---

## Project setup
```
npm install
```

### Lints and fixes files
```
npm run lint
```
