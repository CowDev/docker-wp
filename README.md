```
     ██████╗ ██╗   ██╗██████╗ ██████╗ 
     ██╔══██╗██║   ██║██╔══██╗██╔══██╗
     ██████╔╝██║   ██║██║  ██║██████╔╝
     ██╔══██╗╚██╗ ██╔╝██║  ██║██╔══██╗
     ██████╔╝ ╚████╔╝ ██████╔╝██████╔╝
     ╚═════╝   ╚═══╝  ╚═════╝ ╚═════╝ 
                                                    
    ----------------------------------
```
# Wordpress install
A new WordPress base install using Docker Compose, Gulp and Composer.

## Install instructions
Create a .env based on the example.env.

Run `composer install` to install composer modules and a couple of default plugins.

Install all modules from gulpfile in base theme, if using the [BVDB_base](https://github.com/CowDev/BVDB_base)
`npm install gulp gulp-util dotenv gulp-sass gulp-autoprefixer gulp-crass gulp-uglify gulp-imagemin browser-sync gulp-cache del run-sequence vinyl-ftp --save-dev`
Or use [gulpfile-install](https://www.npmjs.com/package/gulpfile-install)
_Warning, this will not install vinyl-ftp. Install that separately_
