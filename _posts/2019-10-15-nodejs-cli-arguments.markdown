---
layout: post
title:  "Node.js CLI Arguments"
date:   2019-10-16 20:24:36 -0400
last_update: 
categories: dev
---

Throw this into your Terminal or Git Bash:

```bash
echo "hello world"
```

Just like commands such as `cd`, `mv`, or `cp`, **`echo`** accepts an **argument**.

Now, let's look at re-creating it with Node.js.

First, let's create a JavaScript file:

```bash
touch myEcho.js
```

Now, let's open up that file with **VSCode**:

```bash
code myEcho.js
```

And let's put some code in:

```js
console.log(command.argv[2]);
```

Save it, go back into your command line, and run it:

```bash
node myEcho.js "hello world"
```

The `command.argv` refers to an **Array** with the following elements:
 - **`command.argv[0]`** - this will contain the filepath to your Node.js
 - **`command.argv[1]`** - this will contain the filepath to the JavaScript file being called
 - **`command.argv[2]`** - this will contain the first argument value when you execute the JavaScript file
 - **`command.argv[3]`** - this will contain the second argument value when you execute the JavaScript file
 - **`command.argv[4]`** - this will contain the third argument value when you execute the JavaScript file
 - ... and so on, and so on

Please Slack me if you find this confusing, and I'll try to update it accordingly!