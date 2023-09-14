# Regex Tutorial - Matching an Email

In this document, I will be analyzing the components of a Regex expression that was used to match an email address. A Regex, or Regular Expression, is defined as a series of special characters that define a search pattern. 

## Summary

The regular expression that I will be looking at is used to match an email address: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. I am going to break this down piece by piece to explain the different parts of the regex expression, what it means, and what it is doing.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
The anchors of the matching an email regex expression are the "^" and "$" located at the beginning and end of the expression. The "^" indicates the beginning of the string and the "$" indicates the end of the string. 

### Quantifiers
The quantifiers of a regex expression indicate the minimum and maximum number of characters that is required. In the matching an email address regex, we are asking for a minimum of 2 characters and a maximum of 6: {2,6}. Other paramaters can be set using other quantifier symbols including *, +, and ?. In this expression the + quantifier is also used, and is stating that the next character must match the preceeding character one or more times.

### Character Classes
The character class in a regex is used to define a set of characters that can be used in the expression. This expression contains the character class of \d which indicates a single digit from 0-9.

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Sources
https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial

## Author
View my full GitHub profile here: https://github.com/marinadelconte
