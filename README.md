# Quasar Store for Laboratories

Project 

## Init Config

You must edit the ***quasar.conf.js*** file and add yours supabase credentials.

```js
build: {
  env: {
    SUPABASE_URL: 'XXXX',
    SUPABASE_KEY: 'YYYY'
  }
}
```

## Install the dependencies
```bash
yarn
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
yarn run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
