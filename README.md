# Simple Server

Simple Server allows you to easily get a node.js static file server up and running anywhere anytime.


## Installing


1. [Install Node.js](https://github.com/balupton/node/wiki/Installing-Node.js)

1. Install CoffeeScript
		
		npm -g install coffee-script

1. Install Simple Server

		npm -g install simple-server


## Using

To get your `public` folder up and running on `http://localhost:3000` simply type the following into terminal:

	simple-server public 3000
	- or -
	sise public 3000

The first argument is the folder you want to serve, and the second argument is the port to serve from :)


## History

- v0.3 June 30, 2011
	- Added directory listings

- v0.2 June 29, 2011
	- Added Coffee4Clients v0.2
		- CoffeeScript files accessed with the querystring `?js` are compiled server-side

- v0.1 June 3, 2011
	- Initial commit


## License

Licensed under the [MIT License](http://creativecommons.org/licenses/MIT/)
Copyright 2011 [Benjamin Arthur Lupton](http://balupton.com)
