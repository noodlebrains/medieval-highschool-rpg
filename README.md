
# JavaScript Project Construction

The following sequence should leave you with a gulpfile that has all necessary
tasks defined and appropriately configured .gitignore, .jshintrc, bower.json,
and karma.conf.js files.

1. Export the appropriate modules from JS files and import those modules into
other files (like the "-interface" or frontend files).

2. `$ npm init`

3. Install the following packages
    1. `$ npm i gulp --save-dev`
    2. `$ npm i browserify --save-dev`
    3. `$ npm i vinyl-source-stream --save-dev`
    4. `$ npm i gulp-concat --save-dev`
    5. `$ npm i gulp-uglify --save-dev`
    6. `$ npm i gulp-util --save-dev`
    7. `$ npm i del --save-dev`
    8. `$ npm i jshint --save-dev`
    9. `$ npm i gulp-jshint --save-dev`
    10. `$ npm i browser-sync --save-dev`
    11. `$ npm i -g bower (if not already installed globally)`
    12. `$ npm i bower-files --save-dev`
    13. `$ npm i gulp-sass --save-dev`
    14. `$ npm i gulp-sourcemaps --save-dev`
    15. `$ npm i jasmine --save-dev`
    16. `$ npm i karma --save-dev`
    17. `$ npm i karma-jasmine --save-dev`
    18. `$ npm i jasmine-core --save-dev`
    19. `$ npm i karma-chrome-launcher --save-dev`
    20. `$ npm i karma-cli --save-dev`
    21. `$ npm i karma-browserify --save-dev`
    22. `$ npm i karma-jquery --save-dev`
    23. `$ npm i karma-jasmine-html-reporter --save-dev`
    24. `$ npm i watchify --save-dev`
    25. `$ npm i babelify --save-dev`
    26. `$ npm i babel-preset-es2015 --save-dev`
    27. `$ npm i babel-core --save-dev`

    *_OR_*

    Run the following command in your project dir:

    $ npm i gulp browserify vinyl-source-stream gulp-concat gulp-uglify gulp-util del jshint gulp-jshint browser-sync bower-files gulp-sass gulp-sourcemaps jasmine karma karma-jasmine jasmine-core karma-chrome-launcher karma-cli karma-browserify karma-jquery karma-jasmine-html-reporter watchify babelify babel-preset-es2015 babel-core --save-dev

4. add `{"esversion": 6}` to .jshintrc

5. `$ bower init`

6. `$ node_modules/.bin/jasmine init`

7. in package.JSON add the following:
    ```
    "scripts": {
      "test": "jasmine"
    }
    ```
