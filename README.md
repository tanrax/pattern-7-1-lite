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
|   |– _normalize.sass       
|   |– _owl-carousel.sass  
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

## Other variants

- [Pattern 7-1 with Split media](https://github.com/tanrax/pattern-7-1-with-split-media): The best, highly recommended ❤️)
- [Pattern 7-1](https://github.com/tanrax/pattern-7-1): Standard. **Not responsive design**.
- [Pattern 7-1 Lite with Split media](https://github.com/tanrax/pattern-7-1-lite-with-split-media): Simplified version for students or very small web sites.
- [Pattern 7-1 Lite](https://github.com/tanrax/pattern-7-1-lite): Simplified version for students or very small web sites. **Not responsive design**.
