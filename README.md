Fake Twitter API for node.js
===========================================

Drop in replacement for [ntwitter](http://github.com/AvianFlu/ntwitter) that supplies fake data without the need for an Internet connection or OAuth keys. Intended to replace ntwitter in situations where you may have patchy connectivity (conference wifi, while travelling etc.) or when you don't want to/can't get lots of Twitter OAuth keys (interactive demos etc.). Not intended as a full replacement for ntwitter or for generating realistic test data - just as a temeporary replacement in the aformentioned scenarios.

## Installation

Until I publish to npm, you'll just have to download the files and extract them to the node_modules dir of your project.

## Getting started

I'm assuming assuming you already have an app that uses ntwitter. You can refer to ntwitter's [readme](https://github.com/AvianFlu/ntwitter/blob/master/README.md) for info on how to use it.

Once ftwitter is installed, simply change

```
require('ntwitter')
```

to 

```
require('ftwitter')
```

in your app. Hopefully everything should work as it did before, but now with fake data.

## Currently implemented

Steaming.

## Still to implement

Everything else.
