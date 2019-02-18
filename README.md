## How to start
To start development follow this instruction:

* `clone` this repo
* `npm install` all necessary npm packages


## Gulp usage
Available commends for you to type in console:

`gulp` or `gulp serve`  - this will run gulp in browserSync mode, that means gulp will start serwer on your `localhost` and refreash it for you everytime you change `scss`, `js` or `html` file. Using this command will do all the work for you :)

`gulp watch` - runs gulp in watch mode, that will compiles your `custom.scss` into `css/custom.css`

`gulp sass` - compiles sass into CSS & auto-inject into browsers


## Folder Structure
```
| - development/
	| - css/      
	| - images/  
	| - js/
	| - scss/
	| - index.html  
| - package.json
| - gulpfile.js
```

***where:***
`development`  - is used to contain source code.
