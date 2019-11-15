Base Build 
-

A skeleton for static html websites. 
Uses the font awesome library and breakpoint-sass. Grunt is used to concatenate and uglify the scss and js files and to open and keep running the index.php on port 8000.
The footer and header are included through php include function. 

###Prerequisites 
- PHP
- Node-sass
- Grunt

###Local Development SetUp 

Clones all the files in the repository.
```
git clone ssh:https://github.com/katlazarova/base-build.git 
```
Go to the theme directory.
```
cd theme/
```
Generate node modules and download dependencies. 
```
npm install 
```
Run grunt and open the site. 
```
grunt && grunt serve 
```




