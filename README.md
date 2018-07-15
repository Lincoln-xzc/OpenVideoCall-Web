# Open Video Call

> Open Video Call in vanilla Javascript

## Prerequisites

### Create an Account and Obtain an App ID
In order to build and run the sample application you must obtain an App ID:

1. Create a developer account at [agora.io](https://dashboard.agora.io/signin/). Once you finish the signup process, you will be redirected to the Dashboard.
2. Locate the file **src/utils/Settings.js** and replace <#YOUR APP ID#> with the App ID in the dashboard with single or double quotes.

```xml
export const APP_ID = <#YOUR APP ID#>;
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# use eslint and prettier to improve code quality
npm run lint
npm run format

# unit testing
npm run test

# build for production with minification
npm run build
```
