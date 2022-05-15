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


### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
