# A Simple Blog with Sinatra and Active Record ( + some useful tools)

## Goal
We'll be making a blog using Sinatra. 

## See
* [Dan Neumann blog](http://danneu.com/posts/15-a-simple-blog-with-sinatra-and-active-record-some-useful-tools/)
* [GitHub repo](https://github.com/crguezl/sinatra-blog)

## Features

It includes these features:

* Migrations: the ability to apply and rollback changes to our database (like creating our table of posts).
* Show all of our posts on our homepage
* Individual pages for each blog post
* Appropriate forms and buttons to create/update/destroy our blog posts
* Helper methods that let us simplify our templates.
* A place to put our static pages like "About Me".
* A RESTful interface.
* Layouts, partial templates, and regular templates.
* MVC pattern
* Validations on our posts

## Gems Used
We'll use the following gems (see Gemfile):

* sinatra: the framework
* sqlite3: the database
* activerecord: the interface to our database
* sinatra-activerecord: a bridge that lets us use Active Record
* shotgun: a development server that reloads our app code on each request so we don't need to restart the server to see our changes.
* tux: a console that lets us run Ruby code in the environment of our app/database.
