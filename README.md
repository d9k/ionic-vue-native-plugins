# ionic-vue-native-plugins

It's a fork from https://github.com/PaulHalliday/ionic-vue-skeleton-text-example

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# Build for device with capacitor

```
#npx cap init
npx cap add android
npm run build
npx cap copy
npx cap sync
```

Then open android project from android/ folder in Android Developer Studio
