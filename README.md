
> p5.js is a JS client-side library for creating graphic and interactive experiences, based on the core principles of Processing.

p5-manager is a p5js template builder and sketch manager. Built for p5js enthusiasts.

## Quick Start

### Step 0: Install p5-manager

```bash
$ npm install -g p5-manager
```

### Step 1: Initialize a new collection

```bash
$ p5 new my_collection && cd my_collection
$ npm install
```

By excuting this command, it will create a collection directory and some p5 libraries to it. See the output log:

```bash
create : my_collection
create : my_collection/package.json
create : my_collection/gulpfile.js
create : my_collection/libraries
...
```

### Step 2: Generate a p5 project

```bash
$ p5 generate my_project

// or a more cleaner way

$ p5 g my_project
```

This will generate a p5 project folder with basic templates in it:

```bash
create : my_project
create : my_project/sketch.js
create : my_project/index.html
```

### Step 3: Start the server and do your magic!

```bash
npm start
```

Now edit your sketch.js and go to localhost:5555, p5-manager will do the rest!