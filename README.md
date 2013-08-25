# generator-express-simple 
##  please do not use unless you are on an older version of yeoman
A generator for [Yeoman](http://yeoman.io).


## Getting Started

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```
$ npm install -g yo
```

### Yeoman Generators

Yeoman travels light. He didn't pack any generators when he moved in. You can think of a generator like a plug-in. You get to choose what type of application you wish to create, such as a Backbone application or even a Chrome extension.

To install generator-express-simple from npm, run:

```
$ npm install -g generator-express-simple
```

Finally, initiate the generator:

```
$ yo express-simple
```
This will walk you through a series of questions like the type of preprocessors you want too be installed and other modules you want to install.

After everything, run the express server with 

````
$ node app
````
In a separate terminal, run

````
$ grunt
````
This simple command runs the grunt tasks and watches your files.As simple as that.

### express-simple
 express-simple comes preconfigured with less, normalize, cssmin, uglify, jshint, watch.You can edit it as you wish.
 
### As at now it has support for some html preprocessors or templates:
  - [jade](https://github.com/visionmedia/jade)
  - [hamljs](https://github.com/visionmedia/haml.js)
  - [underscore](http://underscorejs.org)

### The css preprocessors supported are : 
  - [less](http://lesscss.org)
  - [scss](https://github.com/sindresorhus/grunt-sass)

### Getting To Know Yeoman

Yeoman has a heart of gold. He's a person with feelings and opinions, but he's very easy to work with. If you think he's too opinionated, he can be easily convinced.

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
