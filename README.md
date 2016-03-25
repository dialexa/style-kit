# Dialexa Style Kit

CSS/ SASS Style base for Dialexa projects


## Installation

<!-- * `npm install --save @dialexa/dialexa-style-kit` -->
Include this line in your bower dependencies...

```
"dialexa-style-kit": "https://github.com/dialexa/style-kit.git"
```


## Importing into your project

There are a couple of ways to import the styles...

1. Add the path for `{dependenciesFolder}@dialexa/style-kit/style-kit/app.scss` to your build pipeline, to build/ concat/ prefix as you see fit.
  > *Recommended Method.* You will have full usage of the Style Kit's SASS helpers.

2. A built and prefixed CSS file can be found at `dist/dialexa-style-kit.css`.
  > *DISCLAIMER:* This method will not allow the use of the Kit's SASS helpers within your custom SASS.
