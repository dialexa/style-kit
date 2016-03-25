# Dialexa Style Kit

CSS/ SASS Style base for Dialexa projects


## Installation

**NPM**
```
npm install --save @dialexa/dialexa-style-kit
```


_or_

**Bower***
Include this line in your bower dependencies...
```
"dialexa-style-kit": "https://github.com/dialexa/style-kit.git"
```


## Importing into your project

There are a couple of ways to import the styles...

1. Add the path for `{dependency_path}/style-kit/app.scss` to your build pipeline, to build/ concat/ prefix as you see fit.
  > **Recommended Method.** You will have full usage of the Style Kit's SASS helpers.

2. A built and prefixed CSS file can be found at `{dependency_path}/dist/dialexa-style-kit.css`.
  > **DISCLAIMER:** This method will not allow the use of the Kit's SASS helpers within your custom SASS. You will only have access to className helpers in your markup.
