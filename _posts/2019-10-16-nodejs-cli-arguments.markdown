---
layout: post
title:  "Node.js CLI Arguments"
author: "Joho"
date:   2019-10-16 20:24:36 -0400
last_update: 
categories: dev
---

I understand that Node.js on the command line can be extremely confusing, and I *know* for a fact that many people are perplexed.  I hope this example can help you all understand!

Throw this into your Terminal or Git Bash:

```bash
echo "hello world"
```

Just like commands such as `cd`, `mv`, or `cp`...

The [**`echo`**](http://linuxcommand.org/lc3_man_pages/echoh.html) command accepts an **argument**.

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
// this will log out the first string passed
console.log(process.argv[2]);
```

The `process.argv` refers to an **Array** with the following elements:
 - **`process.argv[0]`** - this will contain the filepath to your Node.js
 - **`process.argv[1]`** - this will contain the filepath to the JavaScript file being called
 - **`process.argv[2]`** - this will contain the first argument value when you execute the JavaScript file
 - **`process.argv[3]`** - this will contain the second argument value when you execute the JavaScript file
 - **`process.argv[4]`** - this will contain the third argument value when you execute the JavaScript file
 - ... and so on, and so forth

Save it, go back into your command line, and run it:

```bash
node myEcho.js "hello world"
```

So, what you should see after running the above command is something like this:

```bash
joho@clara:~$ node myEcho.js "hello world"
hello world
```

Please Slack me if you find this confusing, and I'll try to update it accordingly!

Credits to the following users for helping out:
 - [@varunmaster](https://github.com/varunmaster/) - for accusing me of being the Terminator because I didn't set the timezone for the site yet, so it shows up as October 17th, but otherwise being pretty useless ;)