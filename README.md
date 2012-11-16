## What?
An extremely basic [restify](http://mcavage.github.com/node-restify/) server.

## Why?
The restify docs include some Hello World code, but not how to run it.  For absolute rookies some more guidance would be useful.

## How?

### Prerequisites

1. Install [node.js](http://nodejs.org/)
1. Clone this repo
1. Run `npm install` to pull down the dependencies

### Running

1. Run `node server.js`
1. Point your browser to `localhost:8080/hello/Roy`, or if you like, run `curl -is http://localhost:8080/hello/Roy -H 'accept: text/plain'`