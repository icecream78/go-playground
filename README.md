<p style="text-align: center;">
	
# Better Go Playground

Improved Go Playground powered by Monaco Editor and React

![alt text](./docs/demo.gif)
</p>

## Features

* 💡 Code autocomplete
* 💾 Load and save files
* 🛠 [WebAssembly](https://github.com/golang/go/wiki/WebAssembly) support (see [latest release notes](https://github.com/x1unix/go-playground/releases/tag/v1.3.0))
* 🌚 Dark theme


And more

## Demo

[http://goplay.x1unix.com/](http://goplay.x1unix.com/)

## Installation

Playground is available via [Docker Hub](https://hub.docker.com/r/x1unix/go-playground) or can be built and run locally (**Go 1.12+** and **Node.js** required):

```
$ git clone https://github.com/x1unix/go-playground.git
$ cd go-playground
$ make
```

To run the playground, go to `target` directory and start the server:

```bash
$ cd target
$ ./playground -f ./data/packages.json -debug
```

Use `-help` to get information about command params
