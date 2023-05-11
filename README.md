[![Netlify Status](https://api.netlify.com/api/v1/badges/cceb5143-7933-4f0a-8eae-5f1f9b63fb3d/deploy-status)](https://app.netlify.com/sites/thriving-twilight-992296/deploys)

# REM Accessibility

This is an example for using `rem` as a font size, or other sizes with the 62.5% font base font size trick.

It also has a couple of `mixins` to help converting a `px` unit to a `rem` unit.

Look in the `styles.scss` file for the use case example, and the `mixins` can be found in the `mixins` folder.

## Initial set up

```
nvm use && yarn && yarn dev
```

#### Yarn dev

```
yarn dev
```

#### Yarn build

```
yarn build
```

###### Notes

- Uses [Parcel.js](https://parceljs.org/docs/) for bundling.
- Hosted on Netlify - [View here](https://thriving-twilight-992296.netlify.app/)