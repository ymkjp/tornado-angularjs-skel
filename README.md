tornado-angularjs-skel
======================

python 3, tornado, angularjs boilerplate code for starting a tornado
http server and developing with angularjs.

### a note

this is for development only, since this is primarily static file
serving it's better to serve your application from nginx or apache. if
you are wanting a quick setup without much fuss then this skeleton
will do.

## requirements

+ python 3.3.x
+ virtualenv

## quickstart

+ initialize virtualenv either via pyenv or your preferred means.
  + `pyenv virtualenv angularjstest`
  + `source ~/.pyenv/versions/angularjstest/bin/activate`
+ `pip install -r requirements.txt`
+ `./app.py --debug`

## view

Visit `http://localhost:9000` to see the rendered intro text.

## author

Adam Stokes <hackr@cypherbook.com>

## license

MIT
