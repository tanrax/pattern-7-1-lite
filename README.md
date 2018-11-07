Pattern Template 7-1 Lite version, an extraordinarily neat architecture that any Web Designer can understand at a glance. Structure with the help of SASS.

# Compile SASS.

## Install

``` bash
yarn global add node-sass
```

## Run

``` bash
node-sass --output-style compressed resources/sass/main.sass css/main.css
```

## Watch: Autocompile if it detects changes 

``` bash
node-sass --watch --source-map true --output-style compressed resources/sass/main.sass css/main.css
```
