# About DMI
DMI (Direct Machine Interface) is a new programming language being developed in progress. Currently based on a Python interpreter.

## Copyright Notice
Although DMI is an open source project, it is affixed as an invention of Dewan Maksudul Islam Mukto. As per the MIT license included in this repository, you are allowed to do anything as long as you comply by its terms.

![logo](https://github.com/dmimukto/dmi/blob/main/dmi-pl-logo.png)

## Example code
To output a line of text/string :
```
display TEXT
```
```
display "Welcome to DMI programming!"
```
To accept input and store it as a variable :
```
input "TEXT_PROMPT"
store input as VARIABLE_NAME:VARIABLE_TYPE
```
```
input "Enter your name:"
store input as username:string
```
To declare conditionals :
```
if VARIABLE_NAME REQUIREMENT,
    IF_TRUE_ACTION_GOES_HERE
orif VARIABLE_NAME REQUIREMENT,
    ELIF_TRUE_ACTION_GOES_HERE
orelse IF_FALSE_ACTION_GOES_HERE
```
```
if username = "Mukto",
    display "Welcome, sir!"
orelse display "Welcome, guest!"
```
