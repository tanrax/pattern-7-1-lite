Pattern Template 7-1 Lite version, an extraordinarily neat architecture that any Web Designer can understand at a glance. Structure with the help of SASS.

``` txt
sass/                    
|
|– _base.sass            
|– _header.sass          
|– _footer.sass          
|– _mixins.sass          
|– _typography.sass      
|– _variables.sass       
|– pages/                
|   |– _home.sass        
|   |– _contact.sass     
|   ...                  
|– vendors/              
|   |– _bootstrap.sass   
|   |– _jquery-ui.sass   
|   ...                  
`– main.sass             
```

# Compile SASS.

## Install

``` bash
yarn global add node-sass
```

## Run

``` bash
node-sass --output-style compressed sass/main.sass css/main.css
```

## Watch: Autocompile if it detects changes 

``` bash
node-sass --watch --source-map true --output-style compressed sass/main.sass css/main.css
```
