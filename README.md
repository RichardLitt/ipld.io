# ipld.io

> The site for IPLD

## Development

### System Preparation

To use this starter project, you'll need the following things installed on your machine.

#### Required

- Ruby and Ruby Gems
- [Jekyll](http://jekyllrb.com/) - `gem install jekyll`
- [Bundler](http://bundler.io/) - `gem install bundler` (mac users may need sudo)
- [NodeJS](http://nodejs.org)
- [GulpJS](https://github.com/gulpjs/gulp) - `npm install -g gulp`
- [Bower](http://bower.io/) - `npm install -g bower`

#### Local Installation

Git clone this repository, or download it into a directory of your choice. Inside the directory run
1. `bower install` (reference: .bowerrc and bower.json)
2. `npm install` (reference: package.json)
3. `bundle install` (reference: Gemfile and Gemfile.lock)

Do all that in one step: `make install`

### Usage

#### Tasks

`npm start`
This will build your Jekyll site, give you file watching, browser synchronization, auto-rebuild, CSS injecting, Sass sourcemaps etc.

`npm run build`
This builds your site for production, with minified CSS and JavaScript. Run this before you deploy your site!

`http://127.0.0.1.xip.io:3000`
Here you can access your site. If you want to access it with your phone or tablet, use the external access address which is showing up in the terminal window.

`http://127.0.0.1.xip.io:3001`
Access the Browsersync UI.
