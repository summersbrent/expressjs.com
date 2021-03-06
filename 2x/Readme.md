
# Express
      
  Insanely fast (and small) server-side JavaScript web development framework
  built on [node](http://nodejs.org) and [Connect](http://github.com/senchalabs/connect).
  
     var app = express.createServer();
     
     app.get('/', function(req, res){
       res.send('Hello World');
     });
     
     app.listen(3000);

## Installation

    $ npm install express

or to access the `express(1)` executable install globally:

    $ npm install -g express

## Quick Start

 The quickest way to get started with express is to utilize the executable `express(1)` to generate an application as shown below:

 Create the app:

    $ npm install -g express
    $ express /tmp/foo && cd /tmp/foo

 Install dependencies:

    $ npm install -d

 Start the server:

    $ node app.js

## Features

  * Robust routing
  * Redirection helpers
  * Dynamic view helpers
  * Content negotiation
  * Focus on high performance
  * View rendering and partials support
  * Environment based configuration
  * Session based flash notifications
  * Built on [Connect](http://github.com/senchalabs/connect)
  * High test coverage
  * Executable for generating applications quickly
  * Application level view options

Via Connect:

  * Session support
  * Cache API
  * Mime helpers
  * ETag support
  * Persistent flash notifications
  * Cookie support
  * JSON-RPC
  * Logging
  * and _much_ more!

## More Information

  * #express on freenode
  * [express-expose](http://github.com/visionmedia/express-expose) expose objects, functions, modules and more to client-side js with ease
  * [express-resource](http://github.com/visionmedia/express-resource) resourceful routing
  * [express-configure](http://github.com/visionmedia/express-configuration) async configuration support
  * [express-messages](http://github.com/visionmedia/express-messages) flash notification rendering helper
  * [express-namespace](http://github.com/visionmedia/express-namespace) namespaced route support
  * [express-params](https://github.com/visionmedia/express-params) param pre-condition functions
  * [express-mongoose](https://github.com/LearnBoost/express-mongoose) plugin for easy rendering of Mongoose async Query results
  * Follow [tjholowaychuk](http://twitter.com/tjholowaychuk) on twitter for updates
  * [Google Group](http://groups.google.com/group/express-js) for discussion
  * Visit the [Wiki](http://github.com/visionmedia/express/wiki)
  * [日本語ドキュメンテーション](http://hideyukisaito.com/doc/expressjs/) by [hideyukisaito](https://github.com/hideyukisaito)
  * [Русскоязычная документация](http://express-js.ru/)
  * Screencast - [Introduction](http://bit.ly/eRYu0O)
  * Screencast - [View Partials](http://bit.ly/dU13Fx)
  * Screencast - [Route Specific Middleware](http://bit.ly/hX4IaH)
  * Screencast - [Route Path Placeholder Preconditions](http://bit.ly/eNqmVs)

## Node Compatibility

Express 1.x is compatible with node 0.2.x and connect < 1.0.

Express 2.x is compatible with node 0.4.x, node 0.6.x and connect 1.x

Express 3.x (_master_ branch) is compatible with node 0.6.x and connect 2.x

## Viewing Examples

First install the dev dependencies to install all the example / test suite deps:

    $ npm install -d

then run whichever tests you want:

    $ node examples/jade/app.js

## Running Tests

To run the test suite first invoke the following command within the repo, installing the development dependencies:

    $ npm install

then run the tests:

    $ make test

## Contributors

```
project: express
commits: 3410
files  : 230
authors: 
 1883	Tj Holowaychuk          55.2%
 1285	visionmedia             37.7%
   72	TJ Holowaychuk          2.1%
   54	Aaron Heckmann          1.6%
   34	csausdev                1.0%
   26	ciaranj                 0.8%
    6	Guillermo Rauch         0.2%
    3	Dav Glass               0.1%
    3	Nick Poulden            0.1%
    2	Jake Gordon             0.1%
    2	Ben Weaver              0.1%
    2	Hunter Loftis           0.1%
    2	Benny Wong              0.1%
    2	Dave Hoover             0.1%
    2	Brian McKinney          0.1%
    2	Daniel Shaw             0.1%
    1	Masahiro Hayashi        0.0%
    1	Matt Colyer             0.0%
    1	Pau Ramon               0.0%
    1	Peter Rekdal Sunde      0.0%
    1	Raynos                  0.0%
    1	Roman Shtylman          0.0%
    1	Teng Siong Ong          0.0%
    1	Viktor Kelemen          0.0%
    1	ctide                   0.0%
    1	ewoudj                  0.0%
    1	isaacs                  0.0%
    1	mgutz                   0.0%
    1	pikeas                  0.0%
    1	shuwatto                0.0%
    1	Justin Lilly            0.0%
    1	Adam Sanderson          0.0%
    1	Andrii Kostenko         0.0%
    1	Arpad Borsos            0.0%
    1	Ashwin Purohit          0.0%
    1	Darren Torpey           0.0%
    1	Greg Ritter             0.0%
    1	Gregory Ritter          0.0%
    1	James Herdman           0.0%
    1	Joe McCann              0.0%
    1	Jonathan Dumaine        0.0%
    1	Jonathan Palardy        0.0%
    1	Jonathan Zacsh          0.0%
    1	8bitDesigner            0.0%
    1	Ken Sato                0.0%
    1	Maciej Małecki          0.0%

```

## License 

(The MIT License)

Copyright (c) 2009-2011 TJ Holowaychuk &lt;tj@vision-media.ca&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
