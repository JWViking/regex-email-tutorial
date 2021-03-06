# Matching an Email - Regex tutorial

This is a tutorial that explains how to use regex to verify vaild email addresses using the expression `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})/`. 

## Summary

A regex (regular expression) is a string of characters, numbers, and letters in a specific sequence that helps to match, locate, and manage text. This tutorial will walk you through the parts of a regex and how you can use it to check if a provided email is in a valid email format.


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

## Regex Components

### Anchors
- This regex uses the anchors `^` and `&`.
- `^` Refers to what is happening at the beginning of a regex string. If it is used before something like "Unicorn", it would look like `^Unicorn` and would find match any strings that start with Unicorn.
- `&` Means matches a string that ends with a specific thing. For example, `sidewalk$`. This would match with any string that ends with sidewalk. (Where the sidewalk ends :)

### Quantifiers
- *, +, ?, and {} are regex quanitifiers.
- This specific regex uses + and {}
- `+ @` Means that the first string is followed by one or more @ symbols. , `+ .` means that the string is followd by one or more `.` symbols.
- {2,6} allows for two to six characters in the previous character set of `[a-z\.]`.

### OR Operator
 - | or []
 - this regex does not contain any OR operators

### Character Classes
- \d (digit), \w (word), \s (whitespace)
- \ means "matches a" and then watever follows. So, a digit, or a word, or a whitespace or a special character.
-  `d` means there is any digit there within the range of 0-9.

### Flags
- /  /
- There are no flags in this regex

### Grouping and Capturing
- ()
- This regex is broken down in to three specific groups: `([a-z0-9_\.-]+)`, `([\da-z\.-]+)`, and `([a-z\.]{2,6})`. `([a-z0-9_\.-]+)` is the section that captures the user email name. `([\da-z\.-]+)` captures the email service that is being used. `([a-z\.]{2,6})` captures ".com" typically.


### Bracket Expressions
- [] means matches a string that contains any of the search values within it.
- `[a-z0-9_\.-]` means it can have any lower case letter from a to z or any digit from 0 to 9 or a "-" or a "_" (underscore) or a special character "."


### Greedy and Lazy Match ***Get help here***
- *, +, {}
- `+`
- `{2,6}`

### Boundaries
- \b, and \B
- This regex does not contain boundaries

### Back-references
- \1
- This reges does not contain back-references

### Look-ahead and Look-behind
- (?=), (?<=)
- There are none of these in this regex

## Author

- Created by Juliana Wilcox, a full stack web developer/junior dev.
- https://github.com/JWViking

