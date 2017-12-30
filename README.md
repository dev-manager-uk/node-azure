# notes

Locally when running with 'npm start' server is started and responsive at:
http://localhost:3000/hello/Marcus
http://localhost:3000/

We have to run it on port 80.


# Initial setup
```
npm install
```

# Project run
```
npm start
```

## Start project in cluster
```
npm start:cluster
```

## Swagger Docs Generation

```
npm run swagger
```

## Test

```
npm run test
```

### Test with coverage reports:

```
npm run test:coverage
```

The coverage report will be saved under ```./coverage``` folder.

## Generate Docs

```
npm run doc
```

The project documentation will be saved under ```./doc``` folder.

## Deploy to Azure

Update App Settings on Azure with the following:

```
WEBSITE_NODE_DEFAULT_VERSION 8.9.3
```
Before pushing to Azure, make sure `node_modules` and `dist` folder are created by running the following

```
npm install
npm run-script build
```
