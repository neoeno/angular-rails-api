# Rails API + Angular Template

Creates a **rails-api** backend with an **angular** frontend. The frontend code will be located in `<your-rails-app>/frontend/`.

## Usage

```
rails-api new <your-app-name> \
  --skip-sprockets \
  --skip-test-unit \
  --template=https://github.com/joshnuss/angular-rails-api/raw/master/template.rb
```

## Features

- [rails-api](https://github.com/rails-api/rails-api)
- [grunt](http://gruntjs.com/)
- [slim](https://github.com/slim-template/slim)
- [sass](http://sass-lang.com/)
- [coffeescript](http://coffeescript.org/)
- [bootstrap](http://getbootstrap.com/)
- [live-reload](http://livereload.com/)
- [rspec](https://relishapp.com/rspec)
- [jbuilder](https://github.com/rails/jbuilder)
- [yeoman](http://yeoman.io/)

## Requirements

- [rails-api](https://github.com/rails-api/rails-api)
- [nodejs](http://nodejs.org/)
- [grunt-cli](http://gruntjs.com/)
- [yeoman](http://yeoman.io/)

## Common Tasks

- To build the frontend: `cd frontend && grunt build`
- To run the frontend server: `cd frontend && grunt serve`
- To run the rails server: `rails server`
- To run the rails specs: `rake spec`
- To run the angular specs: `cd frontend && grunt test`

## Development Mode

In dev mode, you need to run both the frontend node server `grunt serve` and the rails server `rails server`
All requests are served from the frontend server, requests to `/api` are proxied to rails.

## Deployment

Run `grunt build` which copies all files to `/public`. Only rails is needed in production.

## Links

1. [Working with Angular.js and Rails](http://rockyj.in/2013/10/24/angular_rails.html)
2. [grunt-slim](https://github.com/matsumos/grunt-slim)

### Time for a coffee break?

@joshnuss is a freelance software consultant. joshnuss@gmail.com
