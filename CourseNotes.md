# JAVASCRIPT TYPES
# ----------------

1. Number
...* Type in numbers or maths.  12 % 5 = 2 (12 divided by 5 has 2 remaining).
...* NaN - 'Not a Number'
...* For prompts or alerts giving a stored var, use Number(first) to display it as a number.

2. String
...* Use double or single quotes, just be careful of apostrophe's (use backslash before apostrophe if using single quotes). 

3. Boolean
...* True and False.  For 3 = 3, you need to use 3 === 3 : true.  3 !== 3 :false (doesn't equal).

4. Undefined
...* Var hasn't been defined.

5. Null

6. Symbol

7. Object



# JAVASCRIPT COMPARISONS
# ----------------------

* !== (doesn't equal)
* ===	(equals)
* >=
* <=
* >
* <


# JAVASCRIPT VARIABLES
# --------------------

* var 
...* var example = "this is the data that is held by variable example"
...* Needs to start with a letter (apart from $ or _).  If two words, use 'camelCase'.
...* Use shift+enter to go to next line of code.
...* Can be re-assigned cascading style.

JAVASCRIPT CONDITIONALS
-------------------
if
	if (name === "Billy") {
		alert("hi Billy!");
	}
else
	if (name === "Billy") {
		alert("hi Billy!");
	} else {
		alert("hmm I don't know you");
	}
else if
	embed another if statement.


JAVASCRIPT LOGICAL OPERATORS
--------------------
&&
	And
||
	Or
!
	Not
	if (!(name === "Bob")) {
		alert ("Hi Bob");
	}
	!true = false

JAVASCRIPT FUNCTIONS
---------------------
alert () 
	calls function
alert ("Hello")
	calls function with argument "Hello"
Declaring a function
	function name () {}
Function Expression
	var variableName = function() {}
	"anonymous function" because function doesn't have a name.
	Can add a name between 'function' and ().
function functionName(argument) {
	console.log(argument);
	}
	then you call the function with any argument.

function multiply(a, b) {
	return a;
	return a * b;
	return b;
	}
multiply(5, 10);	
	This will return an answer, and ends the function after the first answer.


# OTHER NOTES
# -----------------

* Expression
...* A fragment of code that produces a value.
...* Ends with a semi-colon.

* Using the Console
	clear()
		clears the console
	
* Create pop-up - prompt
...* prompt ( "What is your username" );
...* use in variable:
...* var first = prompt ( "Enter first number" );
...* the will automatically be a string, change to number with:
...* Number( first );

* Create pop-up - alert
...* alert ( "the sum is:" + sum );