CLOSURE

Author's Definition- Closure is basically an inner function that has access to its own variables, 
outer function's variables and global variables.
-------------------------------------------------------------------------------------
DEFINITION- When a function is added inside another function, it's called Closure.
It doesn't only have access to outer function's variables but also to outer function's parameters.
Besides having access to its own variables, closure has access to its outer function variables and also to
global function variables. Closures store refrences instead of actual values to the outer function's variables.
If you have a nested function in your program that means you have a closure in there.

------------EXAMPLE-------------
function address (streetnum, avenue)
{
var address = "Address is ";
function displayFulladdress () {
return address + streetnum + " " + avenue;
}
return displayFulladdress ();
}

address ("120st", "60avn");


-----------------------------------
EXTERNAL REFERENCES-
1. https://www.bing.com/videos/search?q=javascript+closure+&&view=detail&mid=2547C7055577C8E7458A2547C7055577C8E7458A&FORM=VRDGAR
2. http://eloquentjavascript.net/03_functions.html
3. http://www.w3schools.com/js/js_function_closures.asp

