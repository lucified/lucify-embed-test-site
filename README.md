
# Simple site for testing published Lucify embed codes

This project contains a single directory with simple html pages, each for testing a different embed code.

The purpose of this project is to make it easy to test that previously published embed codes which are in use by third parties remain operational.

All public files are in the `www` folder. After adding new files to `www`, Run the `./prepare-index` script to update the index.

## Production site

Available at <http://lucify-embed-test.netlify.com/>

## Running locally

This requires you to have [local-web-server](https://www.npmjs.com/package/local-web-server) installed.

```shell
cd www
ws
```

## Build

The "build" consists only of preparing an index.html page with a file index. Run the build with
```
./prepare-index
```

## Deployment

This project has been set up to automatically deploy via Netlify.
