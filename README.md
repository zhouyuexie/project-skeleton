# project-skeleton
A simple project framework to help you quickly start the project.technology stack:Vue,Webpack,Gulp,ES6,Undescore.

## Install

You just need clone this repertory in your folder.

```shell
git clone https://github.com/zhouyuexie/project-skeleton.git
```

## Usage

Modify `package.json` file `dependencies`.

```js
{
  "dependencies": {
    // ES6
    "babel-core": "6.3.13",
    "babel-eslint": "4.1.6",
    "babel-plugin-transform-async-to-generator": "6.3.13",
    "babel-plugin-transform-class-properties": "6.3.13",
    "babel-plugin-transform-runtime": "6.3.13",
    "babel-preset-es2015": "^6.14.0",
    
    // gulp
    "gulp": "^3.9.1",
    "gulp-autoprefixer": "^3.1.0",
    "gulp-html2jade": "^1.1.2",
    "gulp-notify": "^2.2.0",
    "gulp-rename": "^1.2.2",
    "gulp-sass": "^2.3.2",
    "gulp-uglify": "^1.5.4",
    "gulp-webpack": "^1.5.0",
    
    // webpack
    "webpack": "^1.13.1",

    // webpack plug
    "style-loader": "^0.13.1",
    "css-loader": "^0.23.1",
    "file-loader": "^0.9.0",
    "html-loader": "^0.4.3",
    "sass-loader": "^4.0.0",
    "vue-loader": "^8.5.2",

    // vue
    "vue": "^1.0.26",  
    "vue-resource": "^0.9.3",
    "vue-router": "^0.7.13",
    "vue-validator": "^2.1.5",
    "vuex": "^1.0.0-rc.2",
    
    // underscore
    "underscore": "^1.8.3"
  }
}
```

and then `npm install`.

## Notes

- `dist`:Destination floder,include the Production `.js` file.
- `html`:include your `.html` file.
- `sass`:include your `.sass` or `.scss` file.