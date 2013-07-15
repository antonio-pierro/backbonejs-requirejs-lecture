hands-on-backbone-require-js
============================

## Course Description

This course, divided in three parts, deals with the development of 
[MVC (Model-View-Controller)](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) 
web applications, 
using the [Backbone.js](http://backbonejs.org/) with its extension 
[Backbone.Marionette](http://marionettejs.com/) and the 
[Require.js](http://requirejs.org/) library.

In the first part of the course, 
we examine the concepts of **Backbone.js** and the problems Backbone.js has been designed to solve. 
After introducing the basic notions of [MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) 
web application, such as Models, Views, Collections, 
Events, Listener, Template and Rendering, we write our first *Backbone.js* 
application in order to put in practice the knowledge we acquired. 

However, *Backbone.js* is not a complete framework, 
because it leaves much of the application design, architecture and scalability to the developer.
This is the reason why, 
in the second part of the course, 
we build a much more robust project with great separation of concerns between design and code, combining Backbone.js and its extension, **Backbone.Marionette**.

In the third part of the course, we see in details how to use the library **Require.js** to write - in the javascript code - 
a program organised in modules, each of them in a single file,
with dependent variables which do not pollute the global scope.
Then, we see an alternate approach using routes to determine when modules are loaded 
and how to use Require.js to minifier and optimize your multi-file in javascript into one lean package, in order to use it in production.

## Course Structure
- __MVC__
  - Introduction
  - What is MVC?
  - What does MVC give us?
  - When Do I Need A JavaScript MVC Framework?

- __Backbone.js__
  - What is Backbone.js?
  - Why Consider Backbone.js?
  - Backbone.js in detail:
  - Models
  - Views 
  - Collections
  - Events
  - Routers
  - Inheritance & Mixins
  - Dependencies
  - Namespacing 

- __Exercise 1__: Todo App - Your First Backbone.js App
  - Application HTML
  - Todo model
  - Todo collection
  - Application View

- __Backbone Extensions__
  - Backbone.Marionette
  - __Exercise 2__: Marionette Todo App
  - Is the Marionette implementation of the Todo app more maintainable?

- __Modular Development__
  - Introduction
  - Maintainability problems with multiple script files
  - Organizing modules with RequireJS and AMD
  - Asynchrous Module Definition (AMD) 
  - Writing AMD modules with RequireJS
  - __Exercise 3__: Building a modular Backbone app with AMD & RequireJS 





