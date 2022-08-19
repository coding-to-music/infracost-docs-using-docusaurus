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
