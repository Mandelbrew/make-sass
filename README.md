# make-sass

By *Mandelbrew*

A starting point for a Sass project. This is an experiment to wrap the build process of a Sass application through a Makefile. It's all set up to use node-sass for transpiling SCSS and NPM to manage vendor modules.

It comes pre-configured to install Bootstrap with Autoprefixer.

## Workflow

Setup and install:

        make

Compile, bundle and minify everything together:

        make build
        
Remove built application:

        make clean
        
Remove build applicatin and Node modules

        make distclean
        
## Contact

Send us an email at contact@mandelbrew.com if you have any questions or comments. 
