# Welcome to your Expo app 👋

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Preview build

npx eas build --platform android --profile preview

### Resolve permissions problem on preview build

chmod -R u+rwx android app assets components constants hooks scripts utils && chmod u+rwx *.js *.json *.ts
