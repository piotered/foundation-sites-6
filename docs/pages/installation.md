---
title: Installation
description: There are many ways to install Foundation, but if you're just getting started, we have a few suggestions.
---

## Command-Line Tool

The Node-powered Foundation CLI can install the same template projects for you. Install it with npm:

<div class="callout alert">
  <p>As Foundation for Sites is in alpha, the CLI doesn't yet support this framework.</p>
</div>

```bash
npm install --global foundation-cli
```

Once you've installed the CLI, use the `new` command to start making a new project:

```bash
foundation new
```

---

## CSS Download

If you aren't into Sass, we have a starter template with compiled CSS and JavaScript, as well as a starting `index.html` file for you to hack on. Just unzip and get coding!

<a href="#" class="large button">Download CSS Version</a>

---

## Package Managers

Foundation is available on npm, Bower, Meteor, and Composer. The package includes all of the source Sass and JavaScript files, as well as compiled CSS and JavaScript, in uncompressed and compressed flavors.

- npm: `npm install foundation-sites`
- Bower: `bower install foundation-sites`
- Meteor: `meteor add zurb:foundation-sites`
- Composer: `php composer.phar require zurb/foundation-sites`

### Package Contents

Here's what comes in the package.

- `scss/`: Source Sass files. Use this folder as a load path in Sass.
- `js/`: Source JavaScript files. If you're using a build system, make sure `foundation.core.js` is loaded first.
- `dist/`: Compiled files.
  - `css/`: Compiled CSS files. Includes minified and unminified files.
  - `js/`: Concatenated JavaScript files. Includes minified and unminified files.

---

## Other Integrations

The Foundation community has helped us integrate the framework into Rails, WordPress, Django, and more. Head to our [resources page](http://foundation.zurb.com/sites/resources) to find even more ways to use Foundation.
