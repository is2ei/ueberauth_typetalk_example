# Überauth Typetalk strategy Example
[![Build Status][travis-img]][travis] [![License][license-img]][license]

[travis-img]: https://travis-ci.com/is2ei/ueberauth_typetalk_example.svg?branch=master
[travis]: https://travis-ci.com/is2ei/ueberauth_typetalk_example
[license-img]: http://img.shields.io/badge/license-MIT-brightgreen.svg
[license]: http://opensource.org/licenses/MIT

> Using Überauth for authentication in Phoenix.

This project demonstrates how to use Überauth and Typetalk strategy to provide authentication for a Phoenix application.

+ Typetalk ([ueberauth_typetalk](https://github.com/is2ei/ueberauth_typetalk))

## Setup

1. Retrieve app ids and secrets and set environment variables:

	+ Typetalk ([https://developer.nulab.com/docs/typetalk/](https://developer.nulab.com/docs/typetalk/))
		+ TYPETALK_CLIENT_ID
		+ TYPETALK_CLIENT_SECRET
		+ TYPETALK_REDIRECT_URI

1. Clone the project:

	```shell
	$ git clone git@github.com:is2ei/ueberauth_typetalk_example.git
	$ cd ueberauth_typetalk_example
	```

1. Fetch dependecies:

	```shell
	$ mix deps.get 
	$ cd assets && npm install
	$ npm run deploy
	```

1. Run server:

	```shell
	$ docker-compose -d up
	$ mix phx.server
	```

1. Authenticate at [http://localhost:4000](http://localhost:4000)!

## License

Please see [LICENSE](https://github.com/is2ei/ueberauth_typetalk_example/blob/master/LICENSE) for licensing details.
