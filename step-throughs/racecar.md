# Racecar

Stepping through my solution reversing "racecar".

My solution isn't the most interesting one for step-through-ing.  Basically any valid input will be treated the same.  Solutions using fewer language features and more control flow will be more interesting to step through.

```js
function solution(str){
    var split = str.split(""); 
    var reverse = split.reverse(); 
    return reverse.join("") 
};

var arg = "racecar";

console.log(solution(arg));

```
---

## Step 0 - JavaScript's initial parse
* Memory: (Things the computer knows)
  * arg: _String_ 
  * solution: _Function_
* Operations: (Things the computer does)
  * Created and assigned values to variables.
* Displayed: (Things the user sees)
  * Nothing

---

## Step 1 - Begin executing commands
* Memory: 
  * arg: _String_ 
  * solution: _Function_
* Operations: 
  * Begins executing 'solution' with 'arg' as argument
* Displayed: 
  * Nothing

---

## Step 2
* Memory: 
  * arg: _String_ 
  * solution: _Function_
  * split: _Array_
* Operations: 
  * Splits "racecar" into an array ["r", "a", "c", "e", "c", "a", "r"] and assigns that array to the variable 'split'.
* Displayed: 
  * Nothing

---

## Step 3
* Memory: 
  * arg: _String_ 
  * solution: _Function_
  * split: _Array_
  * reverse: _Array_
* Operations: 
  * Reverses the elements in 'split' - ["r", "a", "c", "e", "c", "a", "r"]. Then creates a new variable called 'reverse' and points it to the same array as 'split'. (Both variables point to the same array in memory.)
* Displayed: 
  * Nothing

---

## Step 4
* Memory: 
  * arg: _String_ 
  * solution: _Function_
  * split: _Array_
  * reverse: _Array_
* Operations: 
  * Builds a new string by concatenating the elements in the array 'reverse' is pointing to. Immediately returns that string.  Exits the function execution.
* Displayed: 
  * Nothing

---

## Step 5
* Memory:
  * arg: _String_ 
  * solution: _Function_
* Operations:
  * Prints the return value ("racecar") from executing solution(arg).
* Displayed:
  * "racecar" is printed to the console.

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>











