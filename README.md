# AngularApp of my TFG in production deployed in Heroku [![Build Status](https://travis-ci.org/enramir/App-Angular-TFG.svg?branch=master)](https://travis-ci.org/enramir/App-Angular-TFG)

## Instructions of deploy

### Preparation of the application in visual code

-With `$ npm install` we install the dependencies in the node_modules / directory, for the node project you are working on.

-`$ ng build` allows you to do any preparation / build tasks required for your project, before it is used on another project.

### Deployment to Heroku

-First we write `$ heroku login`

-Then we write `$ heroku create app-products-angular`

-And we type the following to associate git with Heroku `$ heroku  git: clone -a app-products-angular`

-We add the changes `$ git add .`

-We write a representative message of the commit `$ git commit -am "
deployment app angular"`

-Finally with this command we deploy our app to Heroku `$ git push heroku master` and *happy code :)*

## Application URL

- <https://app-products-angular.herokuapp.com/>

## API documentation

- <https://documenter.getpostman.com/view/10639688/TVKJyvMf>

