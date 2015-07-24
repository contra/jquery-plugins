jquery plugins
============
#### ~ [http://plugins.jquery.com/](http://plugins.jquery.com)

This app is a simple client-side app that allows one to browse and search jquery plugins.
It fetches data from [npmsearch](http://npmsearch.com/) with the keywords *jquery-plugin* and *jqueryplugin*.
npmsearch also provides rankings for plugins(so we don't have to).

Built with [AngularJS](http://angularjs.org) and [gulp](http://gulpjs.com/)

## Contributing

We welcome all contributors! But please read the notes:

### Project structure

To develop, run `npm install`. Everything that is needed both for the client and development will be installed
(other than gulp, but you probably have that installed through `npm install -g gulp`).

The app code is in app/, with index.html in assets/, javascript in js/, and css in css/.

One quirk of this is that the README for the gh-pages branch goes in assets (so it is preserved during deployment).

### Development and deployment

Several tasks are available from gulp for development and deployment:

- `gulp`: Builds the project on the master branch
- `gulp deploy`: Builds the project for production and deploys by pushing to the
[gh-pages](https://github.com/gulpjs/plugins/tree/gh-pages) branch.
An example output is [this](https://github.com/gulpjs/plugins/commit/fa4027f90a725d9caa7971fc00e1d3c4174d2026) commit.
This is safe as only people with push access to the repo can deploy(awesome!).
