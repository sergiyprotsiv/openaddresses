# osmlab addresses

A repository of tools to retrieve and build an open database of addresses for the world.

We are just starting: https://github.com/osmlab/addresses/issues?state=open

## Installation

    # node 0.10.x
    # Install
    npm install

## Use (command line)

    # Test availability of sources
    npm test
    # Download all sources into data/
    npm start

## Use (module)

    var download = require('address-download');
    download({
        test: false, # true for testing availability, false for downloading
        source: <directorypattern>, # source yaml files to download / test
        target: <directory> # target directory
    }, callback)

## Why?

[I](http://github.com/iandees) spent a lot of time tracking down [address data](https://docs.google.com/spreadsheet/ccc?key=0AsVnlPsfrhUIdEVZTzVFalFYYnlvTkc0R05wcUpsWVE&usp=drive_web) and I want to share that work with others.

## License

Although individual sources of data might have their own licenses, the goal is that the database as a whole be released under [Public Domain](http://opendatacommons.org/licenses/pddl/1.0/) license.
