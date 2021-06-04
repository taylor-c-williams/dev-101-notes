Day 3 Notes


Arrow functions are used when passing another argument to a function call

Function call - 

Objects - 

Property - value, textContent, getElementById

Method - A property that is a function

	99% true: 
	* Properties are nouns - Descriptors - Talking about the thing
	* Methods are verbs - Actions - Turning the crank - Parenthesis - Yellow in VS Code/Eslint

Functions are like little machines that run code

* Define Function - Hey Browser, turn the crank whenever X changes
* Function is called by the browser when X changes

* App is a play
* DOM elements are actors
* We are the directors, giving instructions to the DOM

-> Get Properties
-> Add Methods to those properties

~Document Object Model~ - All element actors - All functionality within JS - JS interface 

~Defining a Function~ - Puts the machine together
VS.
~Calling a Function~ - Turns the machine on

> function shout(message) {
> return message.toUpperCase ();
> }
****Function named Shout** takes -message- and returns message as toUpperCase **

Module System - A structured way to pass functions from one file to another - Import a function into one file which has been exported from another 

> export function (-blahblah-,) {
> Function definition();
> }
> 
> import { -blahblah- } from ‘./fileWithExportedFunction.js’;

* VS Code by default won’t put the file extension so make sure to have your “.js” on file names

*Reset CSS* - Removes default browser styles

*Assertions* - Things that should be valid about our tests - true = true

-> “../“ look one directory up

** Testing

// name your test by what it is testing:
	test(‘test that shout uppercases’) (expect) => {
//Arrange
// Set up your arguments and expectations
	const message = ‘hello world’;
	const expected = ‘HELLO WORLD’;
//Act
// Call the function that you’re testing and set 
	const actual = shout(message);
//Expect
//Make assertions about what is expected versus the actual result
	expect.equal(actual, expected);
	})

* Spellcheck plugin?

* You can run eslint in the current directory from the command line 
	eslint .

 >> You can test that the scripts you are importing aren’t broken, etc. 

****

Vertical Slices - Value Orientation 
-> We will build this vertically, meaning we will deliver full functionality for each math operation before moving to the next feature.

* By working horizontally you lose the ability to take what you’ve learned and update (or you won’t want to bc ppl are lazy)


* articulating the UI before starting a project will surface requirements - what is it actually doing? Does it make sense to the user?

### Some VS Code Shorties:
CMD + B = collapse explorer
CMD + dbl click side by side split
OPTION + Up/down Moves line
Shift + Option + Up/down duplicates line







[Back to Readme](../README.md)