This is a cordova project converted from React web-app.

### Guide:

1. Get bundle.js from https://github.com/healthcelerate/hc-reactui on productin mode.

```bash
$ npm run web-dev
```

2. Then, copy bundle.js into this cordova project's www/js folder. And run the following commands.

```bash
$ cordova platform add ios
$ ionic cordova run ios
$ cordova platform add android
$ ionic cordova run android
```
