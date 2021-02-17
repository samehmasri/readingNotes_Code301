# Defining an application
* Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP.

* An application is a collection of source code written in one of these languages, perhaps a framework, and some dependency description that instructs a build system as to which additional dependencies are needed in order to build and run the application.

# Knowing what to execute
* You don’t need to make many changes to an application in order to run it on Heroku. One requirement is informing the platform as to which parts of your application are runnable.

* If you’re using some established framework, Heroku can figure it out. For example, in Ruby on Rails, it’s typically rails server, in Django it’s python <app>/manage.py runserver and in Node.js it’s the main field in package.json.