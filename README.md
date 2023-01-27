# Independent-Project-10-Recap-67-JS-Exercises #


source: https://www.w3schools.com/js/exercise_js.asp?filename=exercise_js_variables1

//JS VARIABLES

## Create a variable called carName, assign the value Volvo to it.
let carName = "Volvo";

## Create a variable called x, assign the value 50 to it.

let x = 50;

## Display the sum of 5 + 10, using two variables: x and y.
let x = 5;
let y = 10;
document.getElementById("demo").innerHTML = x+y;


## Create a variable called z, assign x + y to it, and display the result in an alert box.
let x = 5;
let y = 10; 
let z = x+y;
alert(z);

## On one single line, declare three variables with the following names and values:
firstName = John;
lastName = Doe;
age = 35;
let firstName = "John", lastName = Doe, age = 35;

// JS OPERATORS

## Multiply 10 with 5, and alert the result:

alert(10*5);

## Divide 10 by 2, and alert the result:
alert(10/2);

## Alert the remainder when 15 is divided by 9.
alert(15%9);

## Use the correct assignment operator that will result in x being 15 (same as x = x + y).
let x = 10;
let y = 5;
x+=y;

## Use the correct assignment operator that will result in x being 50 (same as x = x * y).
x = 10;
y = 5; 
x*=y;

//JS DATA TYPES

## Use comments to describe the correct data type of the following variables:

let length = 16; // number
let lastName = "Johnson"; //string
const x ={
firsName = "John",
lastName = "Doe"
}   // object

// JS FUNCTIONS

## Execute the function named myFunction.

function MyFunction (){
alert("Hello world!");
}
myFunction();

## Create a function called "myFunction".
function myFunction(){
alert("Hello world!")
};

## Make the function return "Hello".
function myFunction(){
return "Hello"
}
document.getElementById("demo").innerHTML = myFunction();

## Make the function display "Hello" in the inner HTML of an element with the ID "demo".

function myFuntion(){
document.getElementById("demo").innerHTML = "Hello";
};

// JS OBJECTS

## Alert "John" by extracting information from the person object.

const person = {
firstName: "John",
lastName: "Doe"
};
alert(person.firstName);

## Add the following property and value to the person object: country: Norway.
const person = {
firstName: "John",
lastName: "Doe",
country: "Norway"
};

## Create an object called person with name = John, age = 50.
Then, access the object to alert("John is 50").

const person = {
name: "John",
age: 50}
alert(`${name} + " is " + ${age}`) // alert(person.name + "is" + person.age);


// JS EVENTS

// The <button> element should do something when someone clicks on it. Try to fix it!
<button onclick = "alert('Hello')">Click me.</button>

## When the button is clicked, the function "myFunction" should be executed.

<button onclick ="myFunction()">Click me. </button>

## The <div> element should turn red when someone moves the mouse over it.

<div onmouseover = "this.style.backgroundColor = 'red'"> myDiv.</div>

//JS STRINGS

## Use the length property to alert the length of txt.

let txt = "Hello world!";
let x = txt.length;
alert(x);

// Use escape characters to alert We are "Vikings".
let txt = "We are \"Vikings\"";
alert(txt);

## Concatenate the two strings to alert "Hello World!".

let str1 = "Hello ";
let str2 = "World!";
alert(str1.concat(str2));// alert(str1+str2);

// JS STRING METHODS

## Convert the text into an UPPERCASE text:

let txt = "Hello World!";
txt = txt.toUpperCase();

## Use the slice method to return the word "bananas".

let txt = "I can eat bananas all day";
let x = txt.slice(10, 17);

## Use the correct String method to replace the word "Hello" with the word "Welcome".

let txt = "Hello World";
txt = txt.replace("Hello", "Welcome");

## Convert the value of txt to upper case.
let txt = "Hello World";
txt = txt.toUpperCase();

## Convert the value of txt to lower case.
let txt = "Hello World!";
txt = txt.toLowerCase();

//JS ARRAYS

## Get the value "Volvo" from the cars array.

const cars = ["Saab", "Volvo", "BMW"];
let x = cars[1];

## Change the first item of cars to "Ford".

const cars = ["Volvo", "Jeep", "Mercedes"];
cars[0] = "Ford";

## Alert the number of items in an array, using the correct Array property.

const cars = ["Volvo", "Jeep", "Mercedes"];
alert(cars.length);

// JS ARRAY METHODS

## Use the correct Array method to remove the last item of the fruits array.

const fruits = ["banana", "orange", "apple"];
fruits.pop();

## Use the correct Array method to add "Kiwi" to the fruits array.

const fruits = ["Banana", "Orange", "Apple"];
fruits.push("Kiwi");

## Use the splice() method to remove "Orange" and "Apple" from fruits.

const fruits = ["Banana", "Orange", "Apple", "Kiwi"];
fruits.splice(1,2);

//JS ARRAY SORT

## Use the correct Array method to sort the fruits array alphabetically.

const fruits = ["Banana", "Orange", "Apple", "Kiwi"];
fruits.sort();

// JS DATES

## Create a Date object and alert the current date and time.

const d= new Date();
alert(d);

## Use the correct Date method to extract the year (four digits) out of a date object.

const d = new Date();
year = d.getFullYear();

## Use the correct Date method to get the month (0-11) out of a date object.
const d = new Date();
month = d.getMonth;

## Use the correct Date method to set the year of a date object to 2020.
const d = new Date();
d.setFullYear(2020);

// JS MATH

## Use the correct Math method to create a random number.
let r = Math.random();

## Use the correct Math method to return the largest number of 10 and 20.

let x = Math.max(10, 20);

## Use the correct Math method to round a number to the nearest integer.

let x = Math.round(5.3);

// Use the correct Math method to get the square root of 9.

let x = Math.sqrt(9);

// JS COMPARISON

## Choose the correct comparison operator to alert true, when x is greater than y.

x = 10;
y = 5;
alert(x >  y);

## Choose the correct comparison operator to alert true, when x is equal to y.
x = 10;
y = 10;
alert(x == y);

## Choose the correct comparison operator to alert true, when x is NOT equal to y.
x = 10;
y = 5;
alert(x !=  y);

## Choose the correct conditional (ternary) operator to alert "Too young" if age is less than 18, otherwise alert "Old enough".

let age = n;
let voteable = (age< 18)? "Too young" : "Old enough";
alert(voteable);



//JS CONDITIONS

## Fix the if statement to alert "Hello World" if x is greater than y.

if (x > y){
  alert("Hello World");
};

## Fix the if statement to alert "Hello World" if x is greater than y, otherwise alert "Goodbye".


if (x > y) {
  alert("Hello World");
} else {
  alert("Goodbye");
};


//JS SWITCH


## Create a switch statement that will alert "Hello" if fruits is "banana", and "Welcome" if fruits is "apple".

switch(fruits) {  
	case "Banana":
		alert("Hello")
		break;
 case Apple":
		alert("Welcome")
		break;    
}

## Add a section that will alert("Neither") if fruits is neither "banana" nor "apple".
	switch (fruits){
	case "Banana":
	alert("Hello")
	break;
	case "Apple":
	alert("Welcome")
	break;
	default:
	alert("Neither");
	};

//JS FOR LOOPS

## Create a loop that runs from 0 to 9.
for(let i=0; i<10; i++){
console.log(i)
};

## Create a loop that runs through each item in the fruits array.

const fruits = ["Apple", "Banana", "Orange")

for(x of fruits){
console.log(x)
};

// JS WHILE LOOPS

## Create a loop that runs as long as i is less than 10.

let i = 0;
while (i<10){
console.log(i);
i++
};

## Create a loop that runs as long as i is less than 10, but increase i with 2 each time.

let i = 0;
while (i<10){
console.log(i);
i= i+2;
};

// JS BREAK LOOPS

## Make the loop stop when i is 5.

for (let i =0; i < 10; i++){
console.log(i);
if(i===5){
break;
}
};

## Make the loop jump to the next iteration when i is 5.
for(let i=0; i<10; i++){
if (i===5){
continue;
}
console.log(i);
}

// JS HTML DOM

## Use the getElementById method to find the <p> element, and change its text to "Hello".

<p id = "demo"> </p>
<script>
document.getElementById("demo").innerHTML = "Hello";
</script>

## Use the getElementsByTagName method to find the first <p> element, and change its text to "Hello".

<p id="demo"> </p>

<script>
document.getElementsByTagName("p")[0].innerHTML = "Hello";
</script>

## Change the text of the first element that has the class name "test".

<p class = "test"></p>
<p class = "test"></p>

<script>
document.getElementsByClassName("test")[0].innerHTML = "Hello";
</script>
	
## Use HTML DOM to change the value of the image's src attribute.

<img id="image" scr = "smiley.gif">

<script>
document.getElementById("image").src = "pic_mountain.jpg";
</script>

## Use HTML DOM to change the value of the input field.

<input type = "text" id= "myText" value= "Hello">

<script>
document.getElementById("myText").value = "Have a nice day!";
</script>

## Change the text color of the <p> element to "red".

<p id = "demo"> </p>
<script>
document.getElementById("demo").style.color = "red";
</script>

## Change the font size of the p element to 40 pixels.
<p id="demo"></p>
<script>
document.getElementById("demo").style.fontSize = 40px
</script>

## Use the CSS display property to hide the p element.

<p id = "demo"></p>
<script>
document.getElementById("demo").style.display = "none"
</script>

## Use the eventListener to assign an onclick event to the <button> element.

<button id = "demo">Click me1</button>
<script>
document.getElementById("demo").addEventListener("click", myFunction);
</script>

