Sketeor
=======
## Table of Content

- [What is Sketeor](#what-is-Sketeor)
- [Installation and use](#installation-and-use)
- [Sketeor features](#sketeor-features)
  - [Folder structure](#folder-structure)
  - [Installed packages](#installed-packages)
    - [CoffeeScript](#coffeescript)
    - [Jade](#jade)
    - [BootStrap](#bootstrap)
    - [Less and SaSS](#less-and-sass)
    - [Fonts Awesome](#fontsawesome)
    - [Iron Router](#iron-router)
  - [Suggested packages](#suggested-packages)



** ALPHA STAGE **


## What is Sketeor?

Sketeor is the skeleton of an opinionated Meteor.Js boilerplate. It's goal is to be an easy to use template, to speed up Meteor development.

The main difference from other templates is the default support for **CoffeeScript**, **Jade**, **LESS/SASS** and **Bootstrap** .

## Installation and use

Installing is very very easy. Just type:

`git clone https://github.com/servermeta/sketeor.git PROJECT_NAME`

Where `PROJECT_NAME` is the name of the project you want to create. If Meteor is already installed, you can immediately launch it:

```
cd PROJECT_NAME
meteor
```

Otherwise you can install Meteor with:

```
curl https://install.meteor.com/ | sh
```

I will try to always keep Meteor and the installed packages updated, but in case I fall behind schedule, you can update your project files by typing this command, while being in the project folder:

`meteor update`

Having an always updated skeleton is very useful for people who, like me, happens to work from a slow or mobile connection.

## Sketeor features

### Folder structure

As we aim for [convention over configuration](http://en.wikipedia.org/wiki/Convention_over_configuration), I structured the folder structure to help developers organize their files:


```
.meteor/
client/
  ├── accounts/
  ├── compatibility/
  ├── router/
  └── stylesheets/
    ├── bootstrap/
    ├── bootstrap-ext/
    ├── font-awesome/
    ├── global.less
    ├── mixins.import.less
    └── variables.import.less
  └── views/
    └── dashboard/
      ├── dashboard.html
      ├── dashboard.less
      └── dashboard.js
    └── home/
      ├── home.html
      ├── home.less
      └── home.js
    └── layouts/
      └── mainLayout.html
    ├── footer.html
    ├── header.html
    └── index.html
collections/
  └── items.js
packages/
public/
  ├── fonts/
  └── images/
server/
  ├── views/
  ├── accounts.js
  ├── email.js
  ├── permissions.js
  ├── publications.js
  └── seeds.js
```


### Installed packages

The packages installed by default in Sketeor:

#### CoffeeScript

The latest Coffeescript package

#### Jade

Wonderful mquandalle:jade

#### Less and SaSS

The latest Coffeescript package

#### Bootstrap

via the Less based nemo64:bootstrap

#### Fontsawesome

The official one

#### Iron Router

How could you ship without it?


### Optional Packages

A list of optional, but strongly suggested packages

#### Accounts Password

#### Alanning Roles



