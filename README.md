# CSS3 'Stretchy'

Demo page (https://henderstack.github.io/stretchy/dist/) <https://henderstack.github.io/stretchy/dist/>

A 'rather simple,' pure CSS rotating Mesh example.

There's really nothing to it, aside from CSS.  No JavaScript was abused for the purposes of this litle experiment.

The project source files use:
- Pug (HTML templating)
- SASS (SCSS - for the stylesheet)

# Clone and Run
A Gulpfile is also included, to build and run the project with a simple server with live reloads for changes to the Pug/SASS files (configured to 'localhost:4000'). To get started, simply clone and folow the basic steps:

```sh
$ npm install
$ gulp
```
# Additional Commands

- gulp clean : Cleans the 'dist' directory manually
- gulp dev   : Builds (i.e., transpiles the Pug and SASS files, and moves them to the 'dist' directory
- gulp server : Starts the simple server

License
-----
MIT

**&copy; 2017, Bryan Henderson (henderstack)**
