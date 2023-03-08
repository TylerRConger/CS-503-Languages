# Java Lisp README

This is a simple Lisp interpreter implemented in Java for CS 403/503
Created by: Tyler Conger and Ben Derleth

## Requirements

Must have the Java virtual environment installed on your machine.


## Usage

### String usage:
To run the lisp interpreter on a string simply call the function "finalReturner" with the valid Lisp string attached. This function will then return to you the result of the lisp code that you passed it in the result of a String.

### File Usage:
If you would like to interpret a file simply call the function "fileWriter" which will ask you for a valid file name (in your current directory) read in that file in lisp and then ask you for a new file name where the result of the Lisp code will be placed.


## Test Cases

Test cases are located in the file tests.txt which showcases the input lisp, the expected result and the actual result for various test cases.

To run these tests yourself call function runTests() in main (this is current done by default)

## License

[MIT](https://choosealicense.com/licenses/mit/)