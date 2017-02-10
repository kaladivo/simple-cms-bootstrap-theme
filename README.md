# simple-cms-bootstrap-theme
This is boostrap theme for [simple-css](https://github.com/kaladivo/simple-cms).

## How to use
First install theme it via npm:
```
npm install --save simple-cms-bootstrap-theme
```
Then include paths in config object

```
import {viewsDir, publicDir as viewsPublicDir} from 'simple-cms-bootstrap-theme',
import SimpleCms from 'simple-cms',

...

let administration = SimpleCms({
    viewsDir,
    viewsPublicDir,
    ...
});
```
And that's it!

## How to modify theme
You can clone this repository and modify theme as you wish. This theme was build with sass, if you want to modify sass files you can compile them to css by running `npm run watch`.