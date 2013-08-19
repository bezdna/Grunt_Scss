My Grunt minimal set for Front-end
=============
For generic frontend development. Mostly small to medium projects, and without some heavy JS.

`src` - source of the project, where all the development should happen
	
	src
	- img - images
	- scss - *.scss or *.sass files
	- js - *.js
	- _*.html - part of html

`production` - code we are sending to client. All preprocessors compiled, css-js-images concatenated and minified.

How to run it
=============
- Download NodeJS http://nodejs.org/
- At the NodeJS command prompt, write:
 -- npm install grunt-cli -g
 -- npm install
 -- grunt
