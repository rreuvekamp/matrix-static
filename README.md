Riot Static
===========

### Installation
`git clone` this repository and follow instructions at [getgb.io](https://getgb.io).
Use gb to build the project using `gb build` then execute it from the `bin/` directory.

### Usage
Accepts `PORT=` env variable to determine what port to use, defaulting to port 8000 if one is not specified. Will panic if port is in use.

Accepts 3 command line arguments:

`--config-file=` to specify the config file, defaulting to `./config.json`.

`--create-guest-account` to specify that a guest account should be registered and should be written to `config-file`.

`--homeserver-url` only applies when using `--create-guest-account` and specifies what homeserver to register guest at.


### Support

Currently hosted at https://stormy-bastion-98790.herokuapp.com/

Discussion Matrix Room is [#riot-static:matrix.org](https://matrix.to/#/#riot-static:matrix.org)