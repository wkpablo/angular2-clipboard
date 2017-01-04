# angular2-clipboard

 Angular2  directive for [clipboard.js](http://zenorocha.github.io/clipboard.js/) by [@zenorocha](https://twitter.com/zenorocha)

## Dependencies

+ Angular 2
+ [clipboard.js](https://clipboardjs.com/)

## Install

You can get it on npm.

```
npm install angular2-clipboard --save
```

## Build project

```
1. npm i

2. npm run build
```

## Example

[plunker](http://embed.plnkr.co/PD4Ap8/)


## Contributing 

1. Your commits conform to the conventions established [here](https://github.com/conventional-changelog/conventional-changelog-angular/blob/master/convention.md)
2. This project used [commitizen](https://github.com/commitizen/cz-cli) and [semantic-release](https://github.com/semantic-release/semantic-release) to handle npm version from CI
    + run git add first to add your changes to staging 
    + use `npm run commit` to commit, and CI will do the rest.

## Troubleshooting

If you see the following error message.

`Import assignment cannot be used when targeting ECMAScript 2015 modules. Consider using 'import * as ns from "mod"', 'import {a} from "mod"', 'import d from "mod"', or another module format instead.`

Please check if the module setting in tsconfig.json is set to `commonjs`

Kudos to [Thierry Templier](http://stackoverflow.com/a/36330518/667767) This project is base on his answer on StackOverflow
