# Intro to Flask

## Learning Goals

- Describe the components of a web application framework.
- Build and run a Flask application on your computer.
- Manipulate and test the structure of a request object.
- Extend a Flask application to meet the unique requirements of different projects.

***

## Key Vocab

- **Web Framework**: software that is designed to support the development of
  web applications. Web frameworks provide built-in tools for generating web
  servers, turning Python objects into HTML, and more.
- **Extension**: a package or module that adds functionality to a Flask
  application that it does not have by default.
- **Request**: an attempt by one machine to contact another over the internet.
- **Client**: an application or machine that accesses services being provided
  by a server through the internet.
- **Web Server**: a combination of software and hardware that uses Hypertext
  Transfer Protocol (HTTP) and other protocols to respond to requests made
  over the internet.
- **Web Server Gateway Interface (WSGI)**: an interface between web servers
  and applications.
- **Template Engine**: software that takes in strings with tokenized
  values, replacing the tokens with their values as output in a web browser.

***

## Introduction

In Phase 2, we learned about web applications and React. In Phase 3, we learned
about the fundamentals of Python and SQL. In Phase 4, we are going to use all of
that knowledge as we build Python-based web applications with
[Flask](https://flask.palletsprojects.com/en/2.2.x/), a web microframework.

A web framework is a tool that is designed to support the development of web
applications. This is similar to React, though true web frameworks provide a
degree of scaffolding to direct you in the construction of your project. Certain
frameworks like [Django](https://www.djangoproject.com/) do everything under the
sun: they give you the power of Python, an ORM, a web server, authentication,
and more. Microframeworks like Flask handle some basic functionality, but more
specific duties require **extensions**. SQLAlchemy is a key extension that we
will be using in Phase 4.

While Flask does not come with all of the features that Django does, it is no
less powerful: Flask is built to carry out a web application's duties in the
most simple, Pythonic way possible, which allows it to cooperate with almost
any PyPI library. (That being said, there are still Flask-specific versions
of these libraries- usually named _"Flask-Libraryname"_.)

***

## The History of Flask

![Flask logo with text: "web development, one drop at a time"](https://curriculum-content.s3.amazonaws.com/python/1200px-Flask_logo.png "flask logo")

Flask was originally developed by [Armin Ronacher][armron] as an April Fool's
joke in 2010. His goal was to make the smallest viable web framework and pitch
it for use in production code. He leveraged some of his other projects in the
process: [Werkzeug][werk] (German for "work stuff") as an interface between the
application and server, [Jinja][jinja] to turn Python code into HTML, and
[Click][click], a CLI building tool that we mentioned at the end of Phase 3.

Competing with the well-established and generally beloved Django, he felt that
his proposal would be met with a laugh. After all, Flask didn't do very much.
All of the source code fit comfortably into one file! Much to Ronacher's
surprise, people loved Flask and began submitting hundreds of pull requests on
the repo, suggesting changes to expand its core functionality and compatibility
with different styles of coding.

Ronacher couldn't handle all of these requests himself, so he created [the
Pallets Projects][pp] as a central location for Flask and his other projects.
If you visit the homepage, you'll see the docs for Werkzeug, Jinja, and Click.
This might be a useful page to bookmark, as most of the important documentation
for Phase 4 is right there!

Because it is useful for small and large projects and a wide variety of tasks,
Flask is now the most used Python web framework: It is used at Netflix, Reddit,
Airbnb, Lyft, Uber, and Mozilla, among many, many other companies. Flask isn't
the perfect tool for every task, but we will explore several common use cases
and introduce you to many generalizable key concepts in full-stack web
development.

***

## What to Look Forward to in Phase 4

In Phase 4, we will cover a number of topics in web development:

- Core Components of Python Web Applications
- Web Scraping
- Application Programming Interfaces (APIs)
- Retrieving Data from APIs
- Building APIs with Flask
- Representational State Transfer (REST)
- Forms and Validations
- Client-Server Communication
- Serialization
- Full-Stack Development with Flask and React
- Deploying a Web Application

Coming out of Phase 4, you will know how to build databases, Flask applications,
and React frontends. This will give you all the tools you need to get started
on your capstone project, as well as any other projects you might have in mind.

Happy coding!

## Resources

- [User's Guide - Flask][flask]
- [Armin Ronacher's Thoughts and Writings][armron]
- [Werkzeug - The Pallets Projects][werk]
- [Jinja - The Pallets Projects][jinja]
- [Click - The Pallets Projects][click]
- [Pallets - The Pallets Projects][pp]

[flask]: https://flask.palletsprojects.com/en/2.2.x/
[armron]: https://lucumr.pocoo.org/
[werk]: https://palletsprojects.com/p/werkzeug/
[jinja]: https://palletsprojects.com/p/jinja/
[click]: https://palletsprojects.com/p/click/
[pp]: https://palletsprojects.com/
