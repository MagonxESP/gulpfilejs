# Gulpfilejs
Compile javascript ES6 and SASS using Gulp

## Usage
* Install
    ```sh
    $ npm install --save-dev @magonxesp/gulpfilejs
    ```
* Create the ```gulpfile.js``` file
    ```sh
    $ touch gulpfile.js
    ```
* gulpfile.js   
    ```javascript
    require('@magonxesp/gulpfilejs')({
        js: {
            webpack_config_path: './webpack.config.js',
        },
        scss: {
            src: './scss/style.scss',
            dist: './dist/css',
        }
    });
    ```