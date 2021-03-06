![ga](http://mobbook.generalassemb.ly/ga_cog.png)

# wdi-11-chi _curious-turtles_

---
Title: JS Datatypes up thru Objects<br>
Type: Homework<br>
Creator: Thom Page & Matt Huntington<br>
Modified by: Kristyn Bryan<br>
Adapted by: Reuben Ayres<br>
Competencies: Objects, Arrays, Loops <br>


---
# Homework 3: Objects 


1. Fork this repo
2. In your terminal, go into your folder for today (should be something like `03_14_objects`)
3. Clone your fork of this repo.
4. Cloning will create a folder called wdi-11-hw-3-objects.  Go into that folder: `cd wdi-11-hw-3-objects`. **Do all your work inside of this folder**
5. Make commits as indicated. (`git add -A` and then  `git commit -m "some message"`).
6. When you finish (and if need to pause working on it), push your commits to your fork (`git push origin master`). **Remember: before you push,** make sure you don't have any staged or unstaged changes (when you run `git status`, it should say something like `working tree clean`).
7. Submit by making a pull request. 

---

## Datatypes

### Refresher
So far we have seen:

* Strings
* Numbers
* Booleans
* Arrays
* Objects

When these datatypes are combined, we get a **data structure**, for example, an array that contains objects that each contain booleans.

Let's say you are tasked with creating some software, and it is up to **you** to determine which datatypes and what data structure to use.

### Answer the Following
For each of the following, write which **datatypes** you would use to represent the data, and then give a small example of the **data structure**:

1. A light switch that can be either on or off.
2. A user's email address.
3. A spaceship with a hull, laser blasters, tractor beam, and warp drive.
4. A list of student names from our class.
5. A list of student names from our class, each with a location.
6. A list of student names from our class, each with a location and each with a list of favorite tv shows.

<hr>
&#x1F534; **Commit your work.**<br>
The commit message should read: <br>
"selecting datatypes done".
<hr>

## Take it Easy

1. Make an array that holds all of the colors of the rainbow.
2. Write code that will access "blue" from the rainbow array.
3. Make an object that is called your name and holds the information about your favorite food, a hobby, the name of the town that you live in currently, and your favorite datatype.
4. Write code that will access your hobby from the object that you just created.

<hr>
&#x1F534; **Commit your work.**<br>
The commit message should read: <br>
"created some data structures and accessed some data: done".<br>
or something like that.
<hr>

# Object-ception

With the following object:

```
const inception = {
   reality: {
       dreamLayer1: {
           dreamLayer2: {
               dreamLayer3: {
                   dreamLayer4: {
                       dreamLayer5: {
                           dreamLayer6: {
                               limbo: "Joseph Gordon Levitt"
                          }
                       }
                   }
               }
           }
       }
   }
}
```

Change the value of `limbo` to `null`.

<hr>
&#x1F534; **Commit your work.** <br>
The commit message should read: <br>
"accessed limbo".
<hr>

## Bond Films

### Array of objects:

```
const bondFilms = [
  { "title" : "Skyfall", "year" : 2012, "actor" : "Daniel Craig", "gross" : "$1,108,561,008" },
  { "title" : "Thunderball", "year" : 1965, "actor" : "Sean Connery", "gross" : "$1,014,941,117" },
  { "title" : "Goldfinger", "year" : 1964, "actor" : "Sean Connery", "gross" : "$912,257,512" },
  { "title" : "Live and Let Die", "year" : 1973, "actor" : "Roger Moore", "gross" : "$825,110,761" },
  { "title" : "You Only Live Twice", "year" : 1967, "actor" : "Sean Connery", "gross" : "$756,544,419" },
  { "title" : "The Spy Who Loved Me", "year" : 1977, "actor" : "Roger Moore", "gross" : "$692,713,752" },
  { "title" : "Casino Royale", "year" : 2006, "actor" : "Daniel Craig", "gross" : "$669,789,482" },
  { "title" : "Moonraker", "year" : 1979, "actor" : "Roger Moore", "gross" : "$655,872,400" },
  { "title" : "Diamonds Are Forever", "year" : 1971, "actor" : "Sean Connery", "gross" : "$648,514,469" },
  { "title" : "Quantum of Solace", "year" : 2008, "actor" : "Daniel Craig", "gross" : "$622,246,378" },
  { "title" : "From Russia with Love", "year" : 1963, "actor" : "Sean Connery", "gross" : "$576,277,964" },
  { "title" : "Die Another Day", "year" : 2002, "actor" : "Pierce Brosnan", "gross" : "$543,639,638" },
  { "title" : "Goldeneye", "year" : 1995, "actor" : "Pierce Brosnan", "gross" : "$529,548,711" },
  { "title" : "On Her Majesty's Secret Service", "year" : 1969, "actor" : "George Lazenby", "gross" : "$505,899,782" },
  { "title" : "The World is Not Enough", "year" : 1999, "actor" : "Pierce Brosnan", "gross" : "$491,617,153" },
  { "title" : "For Your Eyes Only", "year" : 1981, "actor" : "Roger Moore", "gross" : "$486,468,881" },
  { "title" : "Tomorrow Never Dies", "year" : 1997, "actor" : "Pierce Brosnan", "gross" : "$478,946,402" },
  { "title" : "The Man with the Golden Gun", "year" : 1974, "actor" : "Roger Moore", "gross" : "$448,249,281" },
  { "title" : "Dr. No", "year" : 1962, "actor" : "Sean Connery", "gross" : "$440,759,072" },
  { "title" : "Octopussy", "year" : 1983, "actor" : "Roger Moore", "gross" : "$426,244,352" },
  { "title" : "The Living Daylights", "year" : 1987, "actor" : "Timothy Dalton", "gross" : "$381,088,866" },
  { "title" : "A View to a Kill", "year" : 1985, "actor" : "Roger Moore", "gross" : "$321,172,633" },
  { "title" : "License to Kill", "year" : 1989, "actor" : "Timothy Dalton", "gross" : "$285,157,191" }
];
```

Yikes. Well, copy the bondFilms **array** of **objects** above into your js file. Use **for loops** and conditionals and methods in order to complete the below:

* Create a new array called `bondTitles` with only the titles of the Bond films, and console.log the new array.

<hr>
&#x1F534; **Commit your work.** <br>
The commit message should read: <br>
"Made an array of bond titles".
<hr>

* Create a new array `oddBonds`, of only the Bond films released on odd-numbered years.

<hr>
&#x1F534; **Commit your work.** <br>
The commit message should read: <br>
"made an array of odd bonds".
<hr>

* Determine the total cumulative gross of the Bond franchise, and console.log the result. _hint_ To make the grosses into usable numbers, look into the `.replace` Javascript method (there are many ways to do this, however). Look into `parseInt` also.

<hr>
&#x1F534; **Commit your work.** <br>
The commit message should read: <br>
"determined the bond films gross".

## Digging Deeper 

### Humdinger challenge

`bondFilms` again!

- Console log the single movie **object** that contains the actor who starred in the least number of films.

Expected result:

```
{ "title" : "On Her Majesty's Secret Service", "year" : 1969, "actor" : "George Lazenby", "gross" : "$505,899,782" }
```

You should arrive at this result by comparing the frequency of actors.

_hint:_ Objects by definition have **unique** keys. Later in the problem you could create a new object wherein all the Bond actors are keys, and unique, with no doubles.

_another hint:_ You might come to a place where you will want to iterate over an object. You can iterate over arrays, but did you know you can iterate over objects?  (_hint within a hint:_ You _did_ know. We talked about iterating over objects today.  What does that word mean, "iterate"?)

You can either use `Object.keys()`, documentation [here - Object.keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)

Or, you can use a `for ... in` loop, documentation [here - for ... in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in)

The idea here is to spend some time thinking about how to solve a problem, coming up with an approach in your mind, or with a piece of paper, before trying to code it out.  

<br>

### More on `for ... in`

The syntax for iterating over an object with `for ... in` is:

```
for (let key in obj) {
	// stuff, such as console.log(key)
}
```

Where `key` is a variable that instantiates for the keys in object, and `obj` is the name
of the object you are iterating over. So, if you just wanted to console.log all the **keys** in the first bondFilms object, you could write:

```
for (let key in bondFilms[0]) {
	console.log(key);
}
```

Also remember, you can use a variable to access a key in an object, with bracket notation:

`obj[key]` will look for the property in the object that corresponds to whatever the
variable `key` is. This is very different to the syntax `obj['key']` (notice the quotes) that will look for a key _named_ key, rather than a variable.

To print all of the **values** in the first bondFilms object, you could write:

```
for (let key in bondFilms[0]) {
	console.log(bondFilms[0][key]);
}
```
Good luck!

<hr>
&#x1F534; **Commit your work.** <br>
The commit message should read: <br>
"Humdinger".

<hr>

#### Congrats! You have completed the homework.  Submit with a pull request. 

#### Read [Eloquent Javascript](http://eloquentjavascript.net/01_values.html), chapters 1 through 4. Chapter 3, and chapter 4 to some extent, might go a little beyond what we've talked about.  It's ok if you're not fully grasping things in chapter 3, but Chapters 1 and 2 should feel like reviewing to you. This is a great thing to read on your phone on the train on the way in.

#### If you read those chapters in Eloquent JavaScript, and you just can't get enough, check out these CSS vids.  

---

## CSS resources 

* [Box Model](https://www.youtube.com/watch?v=HNgdhp1_kEE&index=6&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J), 7:17

* [CSS Display](https://www.youtube.com/watch?v=qjSe_K3agYc&index=7&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J), 6:24

* [Positioning](https://www.youtube.com/watch?v=zH8kjJdvmOs&index=8&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J), 11:57

* [Units of measure I](https://www.youtube.com/watch?v=5axuSSBIMuQ&index=9&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J), 10:25

* [Units of measure II](https://www.youtube.com/watch?v=ZfxNpQm6m2g&index=10&list=PLdnONIhPScST0Vy4LrIZiYKpFNoxgyH7J), 14:27
