## Setup local plugin

```sh
git clone -b feature/update-capacitor-6 git@github.com:taretmch/appsflyer-capacitor-plugin.git
cd appsflyer-capacitor-plugin
npm i & npm run build & npm link
```

## Install plugin to your project

```sh
npm i /path/to/local/appsflyer-capacitor-plugin
npx cap sync
```
