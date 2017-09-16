# SPECIFICATIONS
This document contains the function specification for clean calc

## v0.0.0
```
add: function
	args: 2
		arg1: a number
			purpose: serve as first argument for computation
		arg2: a number
			purpose: serve as second argument for computation
		return: number
			purpose: returns the result of the sum of arguments
		behaviour: Used to perform the sum of 2 numbers parsed in as arguments


subtract: function
	args: 2
		arg1: a number
			purpose: serve as first argument for computation
		arg2: a number
			purpose: serve as second argument for computation
		return: number
			purpose: returns the result of the sum of arguments
		behaviour: Used to perform the subtraction of 2 numbers parsed in as arguments


multiply: function
	args: 2
		arg1: a number
			purpose: serve as first argument for computation
		arg2: a number
			purpose: serve as second argument for computation
		return: number
			purpose: returns the result of the sum of arguments
		behaviour: Used to perform the multiplication of 2 numbers parsed in as arguments

divide: function
	args: 2
		arg1: a number
			purpose: serve as first argument for computation
		arg2: a number
			purpose: serve as second argument for computation
		return: number
			purpose: returns the result of the sum of arguments
		behaviour: Used to perform the division of 2 numbers parsed in as arguments

```


## v0.1.0
```
function operateIntermediary(operation, arg1, arg2) {
	return operation(arg1, arg2);
};

operateIntermediary: function
	args: 3
		operation: string
			purpose: designates which method to call
			arg1: number
				purpose: required operand
			arg2: number
				purpose: optional operand
		return: number
		behavior: calls the right method with arg1 and arg2
		purpose: allows users to access math methods from a single interface
```
