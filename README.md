# sublime-plantuml
PlantUML support for Sublime Text 3

## Features

* file extension
	* .puml
	* .plantuml
* keyword highlighting
	* by simple pattern matching (inaccurate due to no syntax ayalysis)
* build command
	* [Tool] - [Build] generates an SVG file
	* if you need other type of image files, modify PlantUML.sublime-build

## Installation

first, install Graphviz and PlantUML packages.
for example, in the case of macOS:

```sh
$ brew install graphviz
$ brew install plantuml
```

then, clone a working copy from this repository into the plug-in package directory of Sublime Text 3.

```sh
$ git clone https://github.com/nsiena/sublime-plantuml.git PlantUML
```

enjoy ~~drawing~~ writing figures !
