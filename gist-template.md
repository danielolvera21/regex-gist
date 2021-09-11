# Regex Tutorial - Matching an E-mail

Introductory paragraph (replace this with your text)

## Summary

I will be breaking down the responsibilities of indiviual components of this regular expression:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
This expression certifies that a user inputs a valid email address.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
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

^ indicates the start of a string, while $ indicates the end of a string.

### Quantifiers

curly brackets {} set boundaries for number of characters allowed.
{2,6} means between 2 and 6 characters long.

### Character Classes

Characters that exist between []. Any meta character inside brackets becomes a literal character. Ex: a period(.) inside of a [] no longer means any character, but instead means a literal period.

### Flags

### Grouping and Capturing

Parenthesis () are used to capture parts of an expression and separate them into groups.
name@gmail.com
Group 0: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
Group 1: ([a-z0-9_\.-]+)
Group 2: ([\da-z\.-]+)
Group 3: ([a-z\.]{2,6})

### Bracket Expressions

### Greedy and Lazy Match

the quantifiers \* + {} are greedy operators, expand the match as much as possible.

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Daniel Olvera
Github : https://github.com/danielolvera21
