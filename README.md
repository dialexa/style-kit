# Dialexa Style Kit

CSS/ SASS Style base for Dialexa projects


## Installation

### NPM
```
npm install --save @dialexa/style-kit
```


_or_

### Bower
```
bower install --save dialexa-style-kit
```


## Importing into your project

There are a couple of ways to import the styles...

1. Add the path for `{dependency_path}/dist/dialexa-style-kit.scss` to your build pipeline, to build/ concat/ prefix as you see fit.
  > **Recommended Method.** You will have full usage of the Style Kit's SASS helpers.
  >
  > Note: You may need to add `node_modules/@dialexa/style-kit` (or) `bower_components/dialexa-style-kit` to your `includePath` in your SASS compiler/ loader. You will then `@import 'dist/dialexa-style-kit.scss';` in your root `.scss` file.

2. A built and prefixed CSS file can be found at `{dependency_path}/dist/dialexa-style-kit.css`.
  > **DISCLAIMER:** This method will not allow the use of the Kit's SASS helpers within your custom SASS. You will only have access to className helpers in your markup.
