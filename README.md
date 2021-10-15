# parcel2-test

Some late Friday night localhost testing with Parcel 2.


## Notes

- Followed the official [Parcel's Getting started guide](https://parceljs.org/getting-started/webapp) with some tweaks

- NPM package [parcel-namer-custom](https://www.npmjs.com/package/parcel-namer-custom) is used for retaining the folder structure inside the ```/src```
- Used SASS instead of style.css
- Used the following command for building the web app

```
npx parcel build src/index.html --public-url http://localhost/parcel-test --dist-dir ./
```
