# Regex Tutorial

This tutorial will explaine exactly what a regex is. The tutorial will show how to utilize one using a specific regex as an example.

## Summary
Regex stands for regular expression. A regex is typically used for patter recognision.
When the regex , \w+, also known as [a-z] is used. The regex returns any character between a through z. This will be the regex used to explain the various components of a regex. This specefic regex would be used to search for any instance of character is used.
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
The components of [a-z] are:
[]-means one character
a-z- defines the set of values within the string

### Anchors
Anchors are used to solidfy a position of a validation of a specefic value within the regular expressiono. so if ^ is applied to a. Then the only time the value a would be validated is at the start of any given string. 
### Quantifiers
By applying + to \w essentially allows a given string to be matched as much as possible. The quantifier used is ineffiecient due to this. 
### Grouping Constructs
By enclosing \w+ into () would turn (\w+) into a sub expression. A sub expression is simply an expression that is apart of a larger expression. 
### Bracket Expressions
A bracket expression simply declares that all objects within the brackets are a list. So [a-z] is declared that all twenty-six characters in lowercase are in a list. 
### Character Classes
Character classes allow us to use one set of small characters to equate to a larger set.[a-z] would be one example of a character class. 
### The OR Operator
The or operator can be used to match the left or right of the given symbol, |. One such example would be [a|z]. So the matches should return the character a or z. 
### Flags
Flags in regex simply modifies the actions taken during the search. /az/i would search for all denotations and instances of az, wether it be, AZ, aZ, and so forth.
### Character Escapes
A character escape allows one to match common characters used in regex notation such as, \w. \w would equate to [a-z]. 
## Author

My name is Juwon Oh, a current student of the UCSD full-stack webdevelopment program extension. My profile is in the link below. 
https://github.com/Juwonoh41

