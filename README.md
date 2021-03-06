medium-cli [![npm version](https://badge.fury.io/js/mediumcli.svg)](https://www.npmjs.com/package/mediumcli) [![npm](https://img.shields.io/npm/dt/mediumcli.svg)](https://www.npmjs.com/package/mediumcli)
==========

Medium for Hackers - A CLI for reading [Medium](https://medium.com) Stories.

It helps you read awesome medium articles right in your terminal.

![](http://i.imgur.com/nO3RyMT.gif)

Installation
------------

`$ npm install -g mediumcli`

Docs
----
    Usage: medium [options] [command]

    Commands:

    top [options]         List Medium Top Stories
    read <url>            Read the story right in your terminal
    open [options] <url>  Opens it in your browser

    Options:

    -h, --help     output usage information
    -V, --version  output the version number

    top [options]
    n, --number <int>", "specify number of stories

    open [options] <url>
    -a, --app <application>  specify app to open the url. Eg: firefox

Usage
-----
There are three commands available: `medium top`, `medium read`, `medium open`

#### top command
`$ medium top`

List Medium Top Stories

`$ medium top -n 5`

List only top 5 Medium Stories

#### read command
`$ medium read <url>`

Read the story right in your terminal

#### open command
`$ medium open <url>`

Opens it in your browser

`$ medium open -a firefox <url>`

Opens it in the given application, like it opens the url using firefox in above example.


Issues
------

Feel free to submit issues and enhancement requests.


Contributing
------------

medium-cli is written in NodeJs and would love to accept pull requests for any issues or feature request.

[Read more on contributing](./CONTRIBUTING.md).


License
-------

Copyright (c) 2016 Dheeraj Joshi
Licensed under the [MIT license](http://opensource.org/licenses/MIT).
