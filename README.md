Steps to run the site:

    1. Run "npm i"
    2. Run "gulp serve"

///////////////////////////////

For CSS:

    - All updates should be made in the "scss" folder.
    - Gulp will watch all .scss files that are in the "scss" folder, and output to "css/style.min.css"

For JS:

    - Write all js in the "src" folder...this will then compile the es6 into the "dist" folder and minify it into the "minJS" folder.

///////////////////////////////

Additional Info:

    - No need for mamp/xxamp etc, gulp will serve the files.
    - Browsersync is used to automatically reload webpages once changes are saved


    View on local devices and external devices:
        -You will notice after running gulp-serve a local and external url, for example:

            Local: http://localhost:8012
            External: http://192.168.1.154:8012

         You can use this external url on any device to view the site locally.
