# Introduction

This is intended to anyone with no special notion but the will to learn.
Ask questions when you don't understand, search google. It's not complex.

We'll learn here the corner stones of website development, search the details yourself and combine the following suggestions.

All external links are pointing to source sites you can trust; we'll always try to use existing good, timeless explanation of topics.
This guide is non exhaustive, on going and aims at staying relevant and away from trends.

# HTML and CSS

## HTML and CSS are the two fondamentals of the web.
- Do this interactive tutorial before anything else.
[codecademy - HTML and CSS](http://www.codecademy.com/en/tracks/web)
- Also be sure to underastand what is [HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- and [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS).

## A bit of concepts and vocabulary
- A naming convention is a way to name and refer to your elements. It helps you have a previsible and logic structure.
Here we are interested in a [naming convention for CSS](https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md).
You'll use the same in your HTML (since CSS targets HTML elements to style them).
- [Comments (wiki)](http://en.wikipedia.org/wiki/Comment_%28computer_programming%29)
- How a website's layout can adapt itself to any screen size? This is what hides under the concept of responsiveness
[Responsive page with CSS's media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
+ [exemple](http://jsbin.com/zuwedod/edit?html,css,output)
- What are [front-end web development](https://en.wikipedia.org/wiki/Front-end_web_development) and
[back-end](https://en.wikipedia.org/wiki/Front_and_back_ends)

## Where to practice those skills?
Spend some time trying things arround.
- create an acount and do a small exemple page on a fresh [jsbin](http://jsbin.com/).
- create a tumblr theme from scratch using a boilerplate (for the HTML base structure).
Follow the [Get started here](https://www.tumblr.com/docs/en/custom_themes).
And use [this boilerplate](https://github.com/hugovieilledent/tumblr-boilerplate) copying the data at in `index.html`.

# Tools to code
- To edit files containing code, [Atom](https://atom.io).
- [jsbin](http://jsbin.com/?html,css,js,output) - code sharing site, see the result live. Along with the code, the complete _output_ of the code is also displayed. This tool is also very useful to test/bootcamp an idea fast

# Javascript
A language to add actions and user interactions to your website.
Learn it by doing those two tutorials.
- [codecademy interactive Javascript tutorial ](http://www.codecademy.com/en/tracks/javascript)
- [Mozilla Javascript tutorial](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

# Tools
## Frameworks
Frameworks can be usefull, but you don't "have to" use them.
- [What is a software framework?](https://en.wikipedia.org/wiki/Software_framework). Also sometimes usefull as code and style exemples.
- [What is a CSS framework?](http://en.wikipedia.org/wiki/CSS_frameworks); [Exemple: Bootstrap](http://getbootstrap.com/), [html5boilerplate](https://html5boilerplate.com/)
- A Javascript framework, [codecademy's jQuery tutorial](http://www.codecademy.com/en/tracks/jquery).

## CSS pre-compilers
A css pre-compiler (SASS, or LESS) is  a tool which allows developer to enhance CSS.
The only downside is that only pure css can be read by a Web Browser, so you have to compile a SASS file into a CSS file before putting it online - it is a pre-compiler. You will get to use them don't rush.

## Command Line Interface
A software to write instruction to a conmputer, it is central to development.
You'll learn to use it over time, basics are pretty easy, but depend on the
[Operation System](https://en.wikipedia.org/wiki/Operating_system) you are using.
[Learn what a CLI is here)(https://en.wikipedia.org/wiki/Command-line_interface).

- linux: open the `Terminal` app. Works in any [Linux distribution](https://en.wikipedia.org/wiki/Linux_distribution)
- mac: open the "Terminal" application in your mac. All commands here start with a $, but don't write it in the terminal, it is only to show you it is a terminal command (alternative software: [iTerm2](http://iterm2.com/)).
- windows: open `command prompt` application

## Package manager
- [What is it](https://en.wikipedia.org/wiki/Package_manager)
- npm, the javascript package manager. 

## Git
Short story: open source software used by developers to work on a project with multiple developers.
It keeps tracks of changes, who made them, when and what is the latest version of the project's code.
- [What is git](http://en.wikipedia.org/wiki/Git_%28software%29)http://en.wikipedia.org/wiki/Git_%28software%29
- [Try git](https://try.github.io/)https://try.github.io/
- Store your git repos on [Gitlab (free also for private repos)](http://gitlab.com/) or [Github (free if public repos)](http://github.com/)

## FTP

[FTP](http://en.wikipedia.org/wiki/File_Transfer_Protocol) is a protocol of data communication (**http **is also one) and is also a software used to upload data to a server.

## Hosting
Of course you want your work to go online, be able to share a nice URL with friends and beyond.
- [Surge](https://surge.sh/) is a (command line based) free hosting.
- [WebFaction](https://www.webfaction.com/), a more complex but solid solution to host anything — also [Digital ocean](http://digitalocean.com/).

## Images Format for the Web
- Research differences between, .png (transparency) / .svg (vectoriel) / .jpeg

## Units, Sizes, Font sizes
what are all those: px, em, rem, vw, vh?
- **px** are the base unit of the web, but [why should we use em or rem instead?](http://stackoverflow.com/questions/609517/why-em-instead-of-px)
- what are **em** and **rem** [](https://j.eremy.net/confused-about-rem-and-em/)[https://j.eremy.net/confused-about-rem-and-em/](https://j.eremy.net/confused-about-rem-and-em/)
- **vw** and **vh** [](https://css-tricks.com/viewport-sized-typography/)https://css-tricks.com/viewport-sized-typography/
- never use pt for the web, or any other unit

## Box Model
Why? [article 1](http://www.paulirish.com/2012/box-sizing-border-box-ftw/), [article 2](https://css-tricks.com/international-box-sizing-awareness-day/), [article 3](http://en.wikipedia.org/wiki/Internet_Explorer_box_model_bug#Background)

You should copy that code on all your project, as a base, it will make your life easier.

*   /* apply a natural box layout model to all elements, but allowing components to change */
*   html {
*      box-sizing: border-box;
*   }
*   *, *:before, *:after {
*     box-sizing: inherit;
*   }

## Tools (level 2)

- what is normalize.css? why people use 
- what is **bower.js**
- what is **npm **(node packet manager)? how is it used in the stack of the web-developer?
- autoprefixer, why do we need browser prefixes in css?

## Topics to read about to go further

Best practices, concepts, tools…

- what is a server? an ip adress?
- what is crossbrowser code? why do we need it?
- why do we use the word "maintainable" talking about code?
- what is a server request?
- why "retina displays" are a change for developers

## Software Architecture

[The Architecture of Open Source Applications](http://aosabook.org/en/index.html)

_"Architects look at thousands of buildings during their training, and study critiques of those buildings written by masters. In contrast, most software developers only ever get to know a handful of large programs well—usually programs they wrote themselves—and never study the great programs of history. As a result, they repeat one another's mistakes rather than building on one another's successes."_

## Javascript advanced lvl ++

**Promises**

[](http://www.html5rocks.com/en/tutorials/es6/promises/)http://www.html5rocks.com/en/tutorials/es6/promises/

**ES6 **

[](http://www.2ality.com/2014/09/es6-modules-final.html)http://www.2ality.com/2014/09/es6-modules-final.html

[](https://babeljs.io)https://babeljs.io

**What are design patterns?**

[MVP explained](http://guides.emberjs.com/v1.11.0/concepts/core-concepts/) by ember documentation

[Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) by [Addy Osmani](http://twitter.com/addyosmani) [book]

**javascript readings**

[](http://read.humanjavascript.com/)http://read.humanjavascript.com/

[](http://jhusain.github.io/learnrx/)http://jhusain.github.io/learnrx/

## vocabulary

Git

FTP

Ember

Gulp

Grunt

Scss

Sass

MVC

CMS/CMF

DOM

Mime type

Microformats

Error handling

Validators

Lint tools

Ajax

RDFa

[40 Key Computer Science Concepts Explained In Layman’s Terms](http://carlcheo.com/compsci)


## Ember.js

*   [codeschool - Ember.js](https://www.codeschool.com/courses/warming-up-with-ember-js)
*   [A Comprehensive Discussion of EmberJS Services](https://youtu.be/zwb3HvjpG3o)

## Datatypes

**What are data types**

**What kind of data types there are (Strings, Numbers)**
pp
**How much memory is reserved for a particular datatype**

**How does javascript handle the data types**

**What is strongly typed mean**
