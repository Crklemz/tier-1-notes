# tier-1-notes

#Linking files (J avascript, CSS, jQuery) to the html file:--------------------
For Javascriptfiles: <script src="NAME.js" charset="utf-8"></script>
For CSS files
For jQuery files


#Variables, Constants, and Storing Data:---------------------------------------
syntax for creating a variable --> let NAME = VALUE; (js)
let is the declaration and Value is the assignment
when changing the VALIUE, no longer need to declare.
Example:
let dog = 1  
Chris gets another dog
dog = 2 --> didn't need to use 'let' again
End Example
can be a string, number, or boolean

If you try to change a constant after it has been declared, it will give you an error


#Conditionals:-----------------------------------------------------------------
//**Basic format below:
if(conditional) {
  //code if true
}

true, with type conversion --> ==
true, exact match only --> ===
not true --> !=
etc.

//**if else basic format below:
if(conditional) {
  //code if true
}
else {
  //code if false
}

//**else if basic format below:
if(conditional 1) {
  //code if conditional 1 is true
}
else if(conditional 2) {
  //code if conditional 1 is false
  //but conditional 2 is true
}
else {
  //code if all above are false
}

//**Compound conditionals:
"and" = && --> both sides must be true
"or" = || --> either side can be true


#Arrays:-----------------------------------------------------------------------
Syntax: let NAME = [];
example:
let things = ['thing', 'anotherThing', 'yetAnotherThing']; (there is no trailing comma. and if a string, don't forget quotes)
things.length --> 3
accessing values within array:
array[#] --> the numbers start at 0 for the first item in array
ex. from line 63 --> things[1] will be 'anotherThing' because arrays start at 0

Changing an item within an array:
ex. let favFoods = ['Bacon', 'Shrimp', 'Cheese'];
console.log (favFoods); --> will show the favFoods arrays
favFoods[0] = 'Maple Bacon'; --> should change the first item in array to show 'Maple Bacon' instead of 'Bacon'

checking if an item is in array:
array.indexOf ('itemSreachingFor');
if 'itemSearchingFor' is within the array, you will log back a 0 or positive number.
if 'itemSearchingFor' is NOT within the array, you will log a negative number.

adding item to end of array:
arrayName.push('itemToAdd'); --> this will add the item to the end of the arrays

removing the last item of the array:
arrayName.pop(); --> will remove last item in array

adding item to beginning of array:
arrayName.unshift('itemToAdd'); --> will add the new item to the beginning of the array versus the end like the push() function does

remove item from beginning of array:
arrayName.shift(); --> will remove the first item in the array


#Loops:------------------------------------------------------------------------
Loops allow you to do repeated actions/ blocks of code which depend on the conditional being TRUE
While loop: will continue to do the repeated actions WHILE the condition is true
ex.
let index = 0;
const max = 10
//while loop
while (index < max) {
  log ('in while loop:', index);
  index++;   --> this increments the index so it doesn't get stuck in an infinite loop
}



For loop - We tend to use these FOR a number of times - think 'for a number of times', or 'for a number of items'
a couple ways to do this:

for loops:

for (let i=0(creating the variable i); i<max(creating the condition); i++(incrementing what I is so it isn't an infinite loop)) {
 log ('in for loop'. i:', i); --> should show 'in for loop. I: 0' and then 'in for loop. I: 1' and then etc. printed in the console
}//end for

ex:
loop through an array and find match:
ex. hand of cards
let hand = ['q', '3', 'j', '9', '6', 'k', 'A'];
for(let i=0; i<hand.lenght; i++) {
  log ('for loop', hand[i]); --> will log Q, 3, J, 9, 6, K, A
  if(hand [i] === '9') {
    log ('match'); --> will log Q, 3, J, 9, match, 6, k, A
  }
}// end for


for in: --> dealing with index
does almost the same thing as the for loop but a little less code.
ex:
for(i in hand) {
  log( 'for in loop', hand[i]); --> this is still using the index, hence the [i]
}
--> should show the same as for loop - for in loop Q, for in loop 3, for in loop J, etc. until all items are printed in the log one line after another




for of: --> dealing with what's inside the index
rather than giving the index, it gives the object itself.
ex.
for(card of hand) {
  log( 'for of loop', card);
}
--> should show - for of loop, Q, for of loop 3, etc.


#Functions:




#Objects:

const = object {         --> the curly brackets mean its an object

}


#Object notes from class:

const dane = {
  firstName: 'dane'
  favoriteFoods = ['pulled pork', 'beer', 'potato chips']
}

log (dane.firstName); will show dane

log (dane.favoriteFoods[0]); --> should log pulled pork


you can do array of objects:

const dane = {
  firstName: 'dane'
  favoriteFoods = [
  {main: 'pulled pork', drink: 'beer', side: 'potato chips'}
  ]
}

log (dane.favoriteFoods[0].main); --> should log what?????


you could do:

const dane = {
  firstName: 'dane'
  favoriteFoods = [
  {main: 'pulled pork', drink: 'beer', side: 'potato chips'}
  {main: 'french onion soup', drink: 'burgandy', side: 'baked potato'}
  ]
}

function sayHello() {

}

















#jQuery:




document ready is ready after the html tag.So that is why the logs can be out of order
