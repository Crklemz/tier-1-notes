# tier-1-notes

#Linking files (J avascript, CSS, jQuery) to the html file
For Javascriptfiles: <script src="NAME.js" charset="utf-8"></script>
For CSS files
For jQuery files

#Variables, Constants, and Storing Data
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


#Conditionals:
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




#Arrays:
Syntax: let NAME = [];
example:
let things = ['thing', 'anotherThing', 'yetAnotherThing']; (there is no trailing comma. and if a string, don't forget quotes)
things.length --> 3
accessing values within array:
array[#] --> the numbers start at 0 for the first item in array
ex. from line 63 --> things[1] will be 'anotherThing' because arrays start at 0




#Loops:




#Functions:




#Objects:




#jQuery:
