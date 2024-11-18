# Lights out demo
Deployment

Build the project from source, then copy the output into the `dist` folder
E.g. using `parcel`
```
rm -rf dist && parcel build ./src/index.html --public-url https://limeyuzu.github.io/lightsout/
```

Then run the deploy script
```
npm i
npm run deploy
```

The live demo will be available at https://limeyuzu.github.io/lightsout/