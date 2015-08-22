# Aurelia Minimal

This is Aurelia minimal - the absolute minimal set of files required to get Aurelia to work.

In order to get this to work, you need follow these steps:

* Install Node.JS (including NPM)
* npm install -g jspm
* jspm install aurelia-bootstrapper -y

If you are using jspm for the first time, it automatically choses Traceur over Babel as an ES6 transpiler. You should prefer Babel over Traceur. There are two ways to make this choice:

1. Remove the -y at the end of the command and answer the last question with "babel" instead of the default.
2. Before typing the jspm install command, first run:
  * jspm config defaultTranspiler babel
