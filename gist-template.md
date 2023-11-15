# SK-RegexExpo

Regex is short for regular expression. It is a tool used for pattern matching in strings. This is a sequence of characters that outlines a search pattern. With regular expressions you set rules that define which strings are valid or not.

## Summary

I will be covering the regex `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`. This regex is responsible for filtering which strings are emails, based on characters in the sting and other methods.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

anchors in this one includes ^ which signifies the start of the string and $ which menas the end

### Quantifiers

the {2,6} sets the range that the group of characters before should appear in the string 2 to 6 times

### Grouping Constructs

([a-z0-9_\.-]+) group is for the local part of the email
([\da-z\.-]+) group is for the domain name part of the email
([a-z\.]{2,6}) group is for the top-level domain (TLD) part of the email

### Bracket Expressions

[a-z0-9_\.-] bracket expression matches any character within the specified range for the local part
[\da-z\.-] is for any digit or character within the specified range to the domain name.
[a-z\.] is for any lowercase letter or dot for the TLD.

### Character Classes

\d is for any digit.
\a-z is for any lowercase letter.

### Character Escapes

\. matches the dot

## Author

This expression wasnt written by any specfic group of indivual

Shawn Kim, Email:kimshawnj@gmail.com, Github: Ardvark121
