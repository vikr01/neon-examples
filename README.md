# neon-examples

[![Build Status](https://travis-ci.org/neon-bindings/examples.svg?branch=master)](https://travis-ci.org/neon-bindings/examples)

## Table of Contents

|  | Example | Descrption |
| --- | --- | --- |
| 1.|  [hello world](https://github.com/neon-bindings/examples/tree/master/hello-world) | Return a hello world string to Node | 
| 2.|  [primitives](https://github.com/neon-bindings/examples/tree/master/primitives) | Creating JS primitives in Rust |
| 3.|  [arrays](https://github.com/neon-bindings/examples/tree/master/arrays) | Creating and using JS arrays in Rust |
| 4.|  [objects](https://github.com/neon-bindings/examples/tree/master/objects) | Creating and using JS objects in Rust |
| 5.|  [arguments](https://github.com/neon-bindings/examples/tree/master/arguments) | Getting and checking function arguments |
| 6.|  [functions](https://github.com/neon-bindings/examples/tree/master/functions) | Creating and calling JS functions from Rust |
| 7.|  [classes](https://github.com/neon-bindings/examples/tree/master/classes) | Creating classes |
| 8.|  [modules](https://github.com/neon-bindings/examples/tree/master/modules) | Exporting functions, classes, and values |
| 9.|  [json](https://github.com/neon-bindings/examples/tree/master/json) | Handling JSON passed between JS and Rust |
| 10.|  [errors](https://github.com/neon-bindings/examples/tree/master/errors) | Creating and throwing errors |
| 11.|  [async](https://github.com/neon-bindings/examples/tree/master/async) | Creating and scheduling async background tasks in Node's thread pool |
| 12.|  [thread count](https://github.com/neon-bindings/examples/tree/master/thread-count) | Expose the `num_cups` Rust library to JS | 
| 13.|  [fibonacci task](https://github.com/neon-bindings/examples/tree/master/fibonacci-task) | Computing the nth fibonacci number in Rust and passing the result to JS |
| 14.|  [word counting](https://github.com/neon-bindings/examples/tree/master/word-counting) | A word counting demo in Rust and JS with benchmarks |
| 15.|  [sharing binary data](https://github.com/neon-bindings/examples/tree/master/sharing-binary-data) | Handling binary data passed from Node to Rust |
| 16.|  [electron app](https://github.com/neon-bindings/examples/tree/master/electron-app) | A simple electron app using Neon modules |
| 17.|  Bindgen | Planned |

## Setup

```bash
git clone https://github.com/neon-bindings/examples
cd neon-examples

# Compiling and running a single example:
cd primitives
npm install # OR `yarn`
node ./lib/index.js

# Compiling and running all the examples:
npm install -g lerna
lerna bootstrap
lerna run install
cd primitives
node ./lib/index.js
```
