# Convert any website into an app using ionic5-webview
# Website must be responsive to perfectly work

Download or clone project

Run npm install to install dependencies 

Change url in 'home.page.ts' to your desired url

Run ionic serve or ionic serve -l to lunch project

## NOTE

If you run into the error "ERR_OSSL_EVP_UNSUPPORTED"

This is because Node.js is preventing you from using a feature that OpenSSL removed for security reasons

## Workaround

This can be fixed in 2 possible ways:

1. Update Node.js to the latest stable release
2. Use --openssl-legacy-provider optionOpen: This means instaed of running "ionic serve", run "set NODE_OPTIONS=--openssl-legacy-provider && npm run start" instead and the application will load.

Tutorials on [Blog4Dev website](https://www.blog4dev.com/convert-website-into-an-app/)
