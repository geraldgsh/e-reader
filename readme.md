# A Codecademy exercise to demonstrate routing

An AngularJS app for e-reader service.

- The app displays a list of books on the home page.
- When a book is clicked, it takes you to the book's description.
- When a Read button is clicked, it takes you to the book's first chapter. From there, you can use the Forward and Back buttons to read the book.

# Setting up AngularJS development environment on Windows

Short guide on how to setup a development environment for AngularJS on Windows using Grunt and Bower.

## Step 1: Install Git

Git client is required by Bower and NPM for packages that are hosted on Github. The client should be downloaded from the official page.

[![N|Solid](http://rvcode.com/images/posts/angular-windows/install-git.png)]

## Step 2: Install NodeJS

Go to the [downloads](https://nodejs.org/en/download/) page and select “Windows Installer”:

![N|Solid](http://rvcode.com/images/posts/angular-windows/install-node.png)

Launch the installer and use default settings.

## Step 3: Install Grunt CLI, Bower, and Yeoman

Open the command line prompt and execute the following command:

```sh
npm -g install grunt-cli bower yo generator-angular generator-karma
```

It will install Grunt and Bower to system directory so they are available for all projects.

##  Step 4: Generate the project

Use Yeoman AngularJS generator to create a sample application:

```sh
mkdir angular-demo
cd angular-demo
yo angular
```

Answer to all generator questions. Default values should work just fine. Once finished, the following command can be used to run the demo application:

```sh
grunt server
```

A development web server will be launched at http://localhost:9000: 

![N|Solid](http://rvcode.com/images/posts/angular-windows/running.png)

## Step 5: Load your project

Clear contents in app folder and clone your project files into it

Link to app: https://geraldgsh.github.io/e-reader/#/books

License
----

Free to use

