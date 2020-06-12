<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# Project Summary

In this project, we'll provide a variety of JavaScript problems to help improve your skills. We would like you to push yourselves as much as possible.

## Setup

* `Fork` this repository.
* `Clone` your fork.
* Open `./index.html` with your browser.

## Tips and Tricks

One of the biggest tools at the developer's disposal is the browser's built-in debugger. To use it, open `./index.html` with your browser. Another great tool for small and isolated pieces of code is <a href="http://www.pythontutor.com/visualize.html#">Python Tutor</a>. Just make sure to change the code to `JavaScript ES6`.

## Resources

<details>

<summary> <code> Higher Order Functions </code> </summary>

* [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
* [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
* [ForEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

</details>

<details>

<summary> <code> Destructuring </code> </summary>

```js
// Destructuring is a short hand way to access properties as an object and store them as usable variables.
// Consider the following object:

let user = {
  name: 'John',
  age: 33,
  appearance: {
    hairColor: 'Blonde',
    eyeColor: 'Hazel',
    height: {
      onTinder: '6ft. 4in.',
      offTinder: '6ft. 2in.'
    }
  }
}

// Accessing properties off this object might look something like this

let userName = user.name; // 'John'
let userAge = user.age; // 33
let userHairColor = user.appearance.hairColor; // 'Blonde'
let userEyeColor = user.sppearance.eyeColor; // 'Hazel'

// Or, using object destructuring

let { name, age } = user;

// notice here that we have to declare a new destructured object.
// That's because we're pulling values off two separate objects,
// even though they're on the same parent object.

let { hairColor, eyeColor } = user.appearance;

// Destructuring is a shorter, more concise way to access the properties from objects.
// -------------------------

// You can also destructure functional parameters that are objects,
// capturing only the object properties we care about.

let user = {
  name: 'Steven',
  age: 26
}

function greeting(user) {
  return 'Hello ' + user.name;
}

// Or, with destructuring

function greeting({ name }) {
  return 'Hello ' + name;
}

greeting(user); // 'Hello Steven';

```

</details>

<details>

<summary> <code> Spread </code> </summary>

* [Spread Syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax#Syntax)
* [In Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax#Spread_in_array_literals)
* [In Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax#Spread_in_object_literals)

</details>

<details>

<summary> <code> For...In/Delete </code> </summary>

* [For...In](https://www.w3schools.com/jsref/jsref_forin.asp)
* [Delete](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete)

</details>

<details>

<summary><code> Nesting </code></summary>


* [Nesting Loops](https://stackoverflow.com/a/36413506)

</details>

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250">
</p>
