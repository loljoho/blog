---
layout: post
title:  "Switch in JavaScript"
author: "Joho"
date:   2019-10-21 20:48:00 -0400
update: 
categories: dev
---

Quite straightforward here--a (hopefully) brief and succinct explanation of `switch` in JavaScript.

Let's say you wanted to do something like:
```js
// use `prompt()` to get the user's favourite number
var favLetter = prompt('What is your favourite letter?');

// if it is a, they are kinda lame
if (favLetter === 'a') {
  alert('You are kinda lame!');
}

// if it is b, they are definitely lame
else if (favLetter === 'b') {
  alert('You are definitely lame!');
} 

// if it is c, they are awesome
else if (favLetter === 'c') {
  alert('You are awesome!');
}

// otherwise, they are okay
else {
  alert('You are okay.');
}
```

Why write so much code?  Just use a `switch` statement!

```js
// use `prompt()` to get the user's favourite number
var favLetter = prompt('What is your favourite letter?');

// use `switch` to list all the cases
switch (favLetter) {

  // if it is a, they are kinda lame
  case 'a':
    alert('You are kinda lame!');
    break;

  // if it is b, they are definitely lame
  case 'b':
    alert('You are definitely lame!');
    break;

  // if it is c, they are awesome
  case 'c':
    alert('You are awesome!');
    break;

  // otherwise, they are okay
  default:
    alert('You are okay.');
    break;

}
```

Fin.

Credits to the following users for helping out:

 - [@jhadev](https://github.com/jhadev) - for a quick lookover, so if I messed up, blame him ;)