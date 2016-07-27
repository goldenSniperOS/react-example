//Paquetes para Usar en Proyecto

//Podemos comenzar con un npm init -y o sino todos los datos del proyecto

//Modules
npm i -S alt async body-parser colors compression express history morgan react react-dom react-router request serve-favicon socket.io swig underscore xml2js

//Dev
npm i -D babel-core babel-preset-es2015 babel-preset-react babel-register babelify bower browserify gulp gulp-autoprefixer gulp-concat gulp-cssmin gulp-if gulp-less gulp-plumber gulp-sourcemaps gulp-uglify gulp-util vinyl-buffer vinyl-source-stream watchify

//Add to Package JSON
"scripts": {
	"start": "node server.js",
	"watch": "nodemon server.js"
},

"babel": {
	"presets": ["es2015","react"]
}
