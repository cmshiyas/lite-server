# lite-server

to setup lite server in your machine

nstallation and Usage

The recommended installation method is a local NPM install for your project:

$ npm install lite-server --save-dev
$ yarn add lite-server --dev # or yarn
...and add a "script" entry within your project's package.json file:

# Inside package.json...
  "scripts": {    
    "dev": "lite-server"
  },
With the above script entry, you can then start lite-server via:

$ npm run dev

#Global Installation
lite-server can be also installed globally, if preferred:

$ npm install -g lite-server
 
# To run:
$ lite-server
