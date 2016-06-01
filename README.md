
# Test published Lucify embed codes

This project contains a single directory with simple html pages, each for testing a different Lucify embed code.

The purpose of this project is to make it easy to test that previously published embed codes which are in use by third parties remain operational.

All public files are in the `www` folder.

## Production site

Available at <http://lucify-embed-test.netlify.com/>

## Running locally

```shell
npm install
npm start
```

## Build

The "build" consists only of preparing an index.html page with a file index. Run the build with
```
npm run-script build
```

## Deployment

This project has been set up to automatically deploy via Netlify.
