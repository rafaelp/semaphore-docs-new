---
layout: post
title: NodeJS support
category: The Semaphore platform
---
### Configure your project
Your `package.json` file is where the fun starts. The file should contain at least the name and the version of your project. Without those, we can't see how cool your project is. Our friends at Karma have a good [write-up](http://karma-runner.github.io/0.10/plus/semaphore.html) on how a configuration file should look like.

After [adding](/docs/adding-your-github-project-to-semaphore.html) your NodeJS project to Semaphore, the analysis will recognize it and present you with a customization page.

### Supported versions

Semaphore supports the following stable [NodeJS](http://blog.nodejs.org/) versions: `0.8`, `0.10` and `0.11`.

### Semaphore and NPM

When your project is analysed, the customization page will suggest that you use two commands: to [install](https://npmjs.org/doc/install.html) your project dependecies and to run your [test](https://npmjs.org/doc/test.html) script if provided.

```
npm install
npm test
```

If you're adventurous, drop in your own NVM and NPM commands to the mix.
