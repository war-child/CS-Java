# CS-Java
Module 17 - Computer Science for JavaScript/ Regular Expressions

Regex tutorial 

## Summary

Demonstrative tutorial of regular expression components 

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




## Regex Components/

A regex, or regular expression, is a pattern used to match character combinations in strings. The pattern is wrapped in forward slashes /, and it contains several components: anchors, quantifiers, grouping constructs, bracket expressions, character classes, the OR operator, flags, and character escapes. 

### Anchors/

Anchors are special characters used to specify the position of the pattern within the string.

^ (caret): This anchor signifies the beginning of a string.

$ (dollar): This anchor signifies the end of a string.


### Quantifiers/

Quantifiers specify the number of times a pattern must occur for a match.

*: Matches zero or more times.

+: Matches one or more times.

?: Matches zero or one time.

{n}: Matches exactly n times.

{n,}: Matches at least n times.

{n,x}: Matches between n and x times.

Quantifiers are greedy by default, meaning they match as many occurrences as possible. Adding a ? after a quantifier makes it lazy, matching as few occurrences as needed.

### OR Operator/

### Character Classes/

### Flags/

### Grouping and Capturing/

Grouping constructs are used to group parts of a regex pattern. They are defined by parentheses ().

Username Grouping: ([a-z0-9_.-]+)
Matches combinations of lowercase letters, numbers, and special characters _.- before the @ sign.
Domain Grouping: ([\da-z.-]+)
Matches digits, lowercase letters, periods ., or hyphens - for the domain name.
TLD Grouping: ([a-z.]{2,6})
Matches top-level domains with 2 to 6 characters.

### Bracket Expressions/

Bracket expressions, represented by square brackets [], define a range of characters to match. They are also known as positive character groups.

[xyz]: Matches any of the characters x, y, or z.
[a-z0-9]: Matches any lowercase letter or digit.
[_.-]: Matches the special characters _, ., and -.

### Greedy and Lazy Match/

### Boundaries/

### Back-references/

### Look-ahead and Look-behind/

## Author

Created by Warchild

GitHub: https://github.com/war-child/
Email: wolf@lycanthropy.us
