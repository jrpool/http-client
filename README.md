# http-client
Node HTTP client application, fulfilling specs of learnyounode workshop.

## Project Members

[Jonathan Pool](https://github.com/jrpool)

## modules

```
hget.js
```

## Discussion

This application demonstrates the use of the `get` method of Node’s `http` module.

The application fulfills the specifications of the “HTTP Client” workshop of [learnyounode][lyn] curriculum and is part of the HTTP Client module in Phase 2 of the curriculum of [Learners Guild][lg].

If the server replies with any status code other than 200, the application reports the status code. It does not follow redirects.

## Installation and Setup

0. These instructions presuppose that [npm][npm] is installed.

1. Your copy of this project will be located in its own directory, inside some other directory that you may choose or create. For example, to create that parent directory inside your own home directory’s `Documents` subdirectory and call it `projects`, you can execute:

    `mkdir ~/Documents/projects`

Make that parent directory your working directory, by executing, for example:

    `cd ~/Documents/projects`

2. Clone this project’s repository into it, thereby creating the project directory, named `http-client`, by executing:

    `git clone https://github.com/jrpool/http-client.git http-client`

2. Make the project directory your working directory by executing:

    `cd http-client`

3. Install required dependencies (you can see them listed in `package.json`) by executing:

    `npm i`

## Usage and Examples

Enter `node hget «url»`, replacing `«url»` with any URL, to get an output of the chunks of data received by an HTTP client from the resource at that URL, one chunck per line. For example:

`node hget 'http://geezer.pro/main/'`

To perform linting, execute `npm run lint`.

[lg]: https://www.learnersguild.org
[lyn]: https://github.com/workshopper/learnyounode
[npm]: https://www.npmjs.com/
