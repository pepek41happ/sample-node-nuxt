# Sample Application with Nuxt.js

## Deploy on Scalingo

Create an application on https://scalingo.com, then:

```sh
scalingo --app my-app git-setup
git push scalingo master
```

And that's it!

This application is running at this url: https://nuxt.is-easy-on-scalingo.com/

## Deploy in One Click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.osc-fr1.scalingo.com/deploy?source=https://github.com/Scalingo/sample-node-nuxt)

## Running Locally

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
