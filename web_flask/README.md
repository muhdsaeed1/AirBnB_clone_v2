
## WEB FRAMEWORK (WEB FLASK)

A web development framework is a set of resources and tools for software developers to build and manage web applications, web services and websites

What exactly is a web framework?

It is a software framework that was developed in order to simplify the web development process and make it easier to build a website. It includes templating capabilities that allow you to present information within a browser, provides an environment for scripting how information flows and also contains many application programming interfaces (APIs) for gaining access to underlying data resources. Most frameworks also provide tools in order for web developers to build a content management system (CMS) for managing digital information on websites and the Internet

A web application or development framework can be considered as a pre-built structure that handles the more repetitive processes and features involved with developing a website. This means that a web developer will spend most of their time interacting with the different parts of the web framework through the use of code

Frameworks are, in short, libraries that help you develop your application faster and smarter

best frameworks available online, in your preferred language.

1. Ruby on Rails
Ruby on Rails is an extremely productive web application framework written by David Heinemeier Hansson. One can develop an application at least ten times faster with Rails than a typical Java framework. Moreover, Rails includes everything needed to create a database-driven web application, using the Model-View-Controller pattern.

Language: Ruby
Latest Version: Rails 5.0.0.beta2
Framework Link: http://rubyonrails.org
Github Link: https://github.com/rails/rails


 Django
Django is another framework that helps in building quality web applications. It was invented to meet fast-moving newsroom deadlines while satisfying the tough requirements of experienced Web developers. Django developers say the applications are ridiculously fast, secure, scalable, and versatile.

Language: Python
Latest Version: Django 1.9.2
Framework Link: https://www.djangoproject.com
Github Link: https://github.com/django/django

Angular(Also, know as Angular JS)
Angular is a framework by Google (originally developed by Misko Hevery and Adam Abrons) which helps us in building powerful Web Apps. It is a framework to build large scale and high-performance web applications while keeping them as easy-to-maintain. There are a huge number of web apps that are built with Angular.

Language: JavaScript
Latest Version: Angular 7.1.5
Framework Link: https://angular.io/
Github Link: https://github.com/angular/angular


 Laravel
Laravel is a framework created by Taylor Otwell in 2011 and like all other modern frameworks, it also follows the MVC architectural pattern. Laravel values Elegance, Simplicity, and Readability. One can right away start learning and developing Laravel with Laracasts which has hundreds of tutorials in it.

Language: PHP
Latest Version: Laravel 5.2
Framework Link: https://laravel.com/
Github Link: https://github.com/laravel/laravel


Spring
Spring, developed by Pivotal Software, is the most popular application development framework for enterprise Java. Myriads of developers around the globe use Spring to create high performance and robust Web apps. Spring helps in creating simple, portable, fast, and flexible JVM-based systems and applications.

Language: Java
Latest Version: Spring 4.3.0
Framework Link: http://projects.spring.io/spring-framework/
Github Link: https://github.com/spring-projects/spring-framework


What is Flask Python

Flask is a web framework, it’s a Python module that lets you develop web applications easily. It’s has a small and easy-to-extend core: it’s a microframework that doesn’t include an ORM (Object Relational Manager) or such features.

It does have many cool features like url routing, template engine. It is a WSGI web app framework.

Flask is a web application framework written in Python. It was developed by Armin Ronacher, who led a team of international Python enthusiasts called Poocco. Flask is based on the Werkzeg WSGI toolkit and the Jinja2 template engine.Both are Pocco projects.

WSGI
The Web Server Gateway Interface (Web Server Gateway Interface, WSGI) has been used as a standard for Python web application development. WSGI is the specification of a common interface between web servers and web applications.

Werkzeug
Werkzeug is a WSGI toolkit that implements requests, response objects, and utility functions. This enables a web frame to be built on it. The Flask framework uses Werkzeg as one of its bases.

jinja2
jinja2 is a popular template engine for Python.A web template system combines a template with a specific data source to render a dynamic web page.

This allows you to pass Python variables into HTML templates like this


<html>
    <head>
        <title>{{ title }}</title>
    </head>
    <body>
        <h1>Hello {{ username }}</h1>
    </body>
</html>


Microframework
Flask is often referred to as a microframework. It is designed to keep the core of the application simple and scalable.

Instead of an abstraction layer for database support, Flask supports extensions to add such capabilities to the application

Why is Flask a good web framework choice?
Unlike the Django framework, Flask is very Pythonic. It’s easy to get started with Flask, because it doesn’t have a huge learning curve.

On top of that it’s very explicit, which increases readability. To create the “Hello World” app, you only need a few lines of code.

This is a boilerplate code example.


from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello World!'

if __name__ == '__main__':
    app.run()


    f you want to develop on your local computer, you can do so easily. Save this program as server.py and run it with python server.py


    $ python server.py
 * Serving Flask app "hello"
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)


 It then starts a web server which is available only on your computer. In a web browser open localhost on port 5000 (the url) and you’ll see “Hello World” show up.
To host and develop online, you can use PythonAnywhere
