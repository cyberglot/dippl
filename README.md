## The Design and Implementation of Probabilistic Programming Languages

A web book, available online at [dippl.org](http://dippl.org/)

Requirements:

- [git](http://git-scm.com/)
- [nodejs](http://nodejs.org)
- [jekyll](http://jekyllrb.com/)

Installation:

    git clone https://github.com/probmods/dippl.git
    cd dippl
    git submodule update --init --recursive
    npm install
    npm install -g browserify bower uglifyjs
    bower install

Run local webserver:

    jekyll serve --watch

Update webppl:

    cd /PATH/TO/webppl
    grunt compile
    mv compiled/webppl.min.js /PATH/TO/dippl/assets/js/webppl.min.js

## Assets

- webppl: 258bea8 (v0.7.0 daipp)
- webppl-editor: 95236b9
- webppl-viz: 2450784
