# Goose Ninja Pixi.js tutorials

This is the source code for my pixi.js tutorials posted on my website http://goose.ninja

Some of these tutorials need to serve static files and to get this working you have to do just that.
There are many different ways of doing this, and you may do it however you want, but here are some very simple one liners to run from your terminal.

Just start by going in to the project folder.
```
    $ cd pixijs_tutorial
```
Then depending on what you want to use type

### Python 2
```
    $ python -m SimpleHTTPServer 8080
```
### Python 3
```
    $ python3 -m http.server 8080
```
### Ruby
```
    $ ruby -run -e httpd . -p 8080
```
### php
```
    $ php -S localhost:8080
```

And then you can see your outcome at
```
    http://localhost:8080
```
