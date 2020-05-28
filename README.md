Parchment Co-Op
=========

Shared web chatroom and console for playing text adventures (Interactive Fiction). Allows all page visitors to send commands to game and communicate with each other without installing any clients. Based on Socket.IO and Parchment JS.


Parchment for Inform 7
----------------------

[Inform 7](http://inform7.com/) includes Parchment, allowing you to produce [personal websites for your stories](http://inform7.com/learn/man/doc394.html). If you want to update the version of Parchment used by Inform 7, grab [parchment-for-inform7.zip](https://raw.github.com/curiousdannii/parchment/master/lib/parchment-for-inform7.zip) and unzip it into the Templates subfolder of your project's Materials folder.

Building Parchment
-----------------

This project uses [Node.js](http://nodejs.org/) and [Grunt](http://gruntjs.com/) to build and test. Install Node.js, and then install the grunt-cli package:

```
npm install -g grunt-cli
```

Then from the Parchment directory install dependencies:

```
npm install
```

To build everything run the following:

```
grunt
```