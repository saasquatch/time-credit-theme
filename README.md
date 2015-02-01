Time Credit Theme
=================

A generic time credit theme for Referral Saasquatch


Setup
-----

To get started, clone the project, install the npm dependencies and start the server.

The serve task will compile less and handlebars on changes and reload the page if you install the plugin for  [LiveReload](http://livereload.com/).

```
git clone git@github.com:saasquatch/time-credit-theme.git
cd time-credit-theme
npm install
gulp serve
```

Mock Customer Data
------------------

Example mock customer data can be found in `customer.json`.  In the dev environment this data is added to the handlebars context with the `gulp-compile-handlebars` plugin.
