# Regex Tutorial

This is a tutorial to explain regular expressions (Regex) and the uses of it

## Summary

Regex, short for regular expression, is often used in programming languages for matching patterns in strings,
find and replace, input validation, and reformatting text. Learning how to properly use Regex can make working with text much easier.

- Example: ^[a-zA-Z0-9]+([._]?[a-zA-Z0-9]+)\*$

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

Anchors are part of the family of regex tokens that do not match any characters, but that also assert something about a string or the matching process.
Anchors also assert that engine's current position in a string matches a well determined location like the beginning of a string or the end of a line

### Quantifiers

Regex Quantifiers are used to quantify how many times a part of the regular expression should be repeated. Every time the user wants to repeat something in a regex (whether it be an individual character, a character class or a sub expression) you can then write a quantifier after to specify how many times it should be repeated.

### OR Operator

Regex recognizes range expressions inside of a list. They represent those characters that fall between the two elements in the current sequence. The user will form a range expression by puttiung a range operator (-) between two characters.

### Character Classes

A character class is a set of characters that are enclosed within square brackets. It specifies the characters that will be successfully matched with a single character from a given input string.

### Flags

In regex, a flag is an optional parameter that modifies its behavior of searching. A flag will change the default searching behavior or a regular expression. It makes a regex search in a different way. A flag is denoted by using a single lowercase alphabetic character.

### Grouping and Capturing

Grouping in regex takes multiple patterns as a whole and groups them together. Capturing groups then provides extra submatch information when using a reular expression pattern to match against a string.

### Bracket Expressions

Bracket expressions [] denotes a character class where () expressions denotes a capturing group.

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

My name is Garen Demirdogen and I am currently enrolled in a coding boot camp via Columbia University. My goal is to become a software engineer and work my dream job in the coding field.

- GitHub Profile: https://github.com/Garendemirdogen
