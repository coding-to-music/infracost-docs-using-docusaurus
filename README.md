# infracost-docs-using-docusaurus

# 🚀 Infracost docs built using Docusaurus 2 🚀

https://github.com/coding-to-music/infracost-docs-using-docusaurus

From / By InfraCost https://github.com/infracost/docs

https://github.com/infracost/docs

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/infracost-docs-using-docusaurus.git
git push -u origin main
```

# Infracost Docs

This website is built using [Docusaurus 2](https://v2.docusaurus.io/).

### Installation

```
nvm use
npm install
```

### Local Development

```
npm start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Update the version mentioned in docs/docs/getting_started.md as some users with old brew caches don't get the latest infracost.

Merges to master automatically update www.infracost.io

Check that the image loads on https://cards-dev.twitter.com/validator for new blog post URLs

### Attempted to upgrade Docusaurus

```
npm i @docusaurus/core@latest @docusaurus/mdx-loader@latest @docusaurus/plugin-client-redirects@latest  @docusaurus/plugin-google-gtag@latest @docusaurus/preset-classic@latest @docusaurus/theme-classic@latest @docusaurus/theme-common@latest

```

Then

got message about

```
[INFO] Starting the development server...
[ERROR] Error: The "gtag" field in themeConfig should now be specified as option for plugin-google-gtag. For preset-classic, simply move themeConfig.gtag to preset options. More information at https://github.com/facebook/docusaurus/pull/5832.
```

commented out the below section in `docusaurus.config.js`

```
    // gtag: {
    //   trackingID: '',
    //   anonymizeIP: true,
    // },

```

```
npm start
```

Output:

```
> infracost-docs-using-docusaurus@0.0.0 start
> docusaurus start

[INFO] Starting the development server...
[ERROR] Can't format blog post date "Invalid Date"
[ERROR] Processing of blog source file "2020-08-17-infracost-cloud-costs-for-devs.md" failed.
[ERROR] RangeError: Invalid time value
```
