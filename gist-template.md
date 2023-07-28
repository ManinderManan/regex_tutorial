# Regex-Turorial Match Email

A regular expression, or Regex, is a sequence of characters that defines a specific search pattern. When it is incorportated into code or search algorithms, regular expressions can be utilized to locate and subsititue a character or sequence of characters within a string. Regular expressions are cmmonly employed for input validation purposes.

Gist regular expression for matching an email address: 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


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
This regular expression uses two anchors, the caret (^) and the dollar sign ($). The caret is used to match the beginning of a string and the dollar sign is used to match the end of a string. In this regular expression, the caret is used to match the beginning of the email address and the dollar sign is used to match the end of the email address.

### Quantifiers
This regular expression uses two quantifiers, the plus sign (+) and the curly braces ({2,6}). The plus sign is used to match one or more of the preceding token. In this regular expression, the plus sign is used to match one or more of the preceding token, which is the character class [a-z0-9_\.-]. The curly braces are used to match the preceding token for a specific number of times. In this regular expression, the curly braces are used to match the preceding token, which is the character class [a-z\.], for a specific number of times, which is 2 to 6 times.

### OR Operator
This regular expression uses one OR operator, which is the pipe (|). The pipe is used to match either the expression before or after the pipe. In this regular expression, the pipe is used to match either the expression before the pipe, which is the character class [\da-z\.-], or the expression after the pipe, which is the character class [a-z\.].

### Character Classes
This regular expression uses four character classes, which are the square brackets ([]). The first character class is [a-z0-9_\.-], which matches any lowercase letter, any digit, the underscore, the period, and the hyphen. The second character class is [\da-z\.-], which matches any digit, any lowercase letter, the period, and the hyphen. The third character class is [a-z\.], which matches any lowercase letter and the period. The fourth character class is [a-z\.], which matches any lowercase letter and the period.

### Flags
This regular expression uses one flag, which is the g flag. The g flag is used to perform a global match, which means that the regular expression will match all occurrences of the pattern in a string.

### Grouping and Capturing
This regular expression uses three groups, which are the parentheses (()). The first group is ([a-z0-9_\.-]+), which matches any lowercase letter, any digit, the underscore, the period, and the hyphen for one or more times. The second group is ([\da-z\.-]+), which matches any digit, any lowercase letter, the period, and the hyphen for one or more times. The third group is ([a-z\.]{2,6}), which matches any lowercase letter and the period for 2 to 6 times.

### Bracket Expressions
This regular expression uses four bracket expressions, which are the square brackets ([]). The first bracket expression is [a-z0-9_\.-], which matches any lowercase letter, any digit, the underscore, the period, and the hyphen. The second bracket expression is [\da-z\.-], which matches any digit, any lowercase letter, the period, and the hyphen. The third bracket expression is [a-z\.], which matches any lowercase letter and the period. The fourth bracket expression is [a-z\.], which matches any lowercase letter and the period.

### Greedy and Lazy Match
This regular expression uses one greedy match, which is the plus sign (+). The plus sign is used to match one or more of the preceding token. In this regular expression, the plus sign is used to match one or more of the preceding token, which is the character class [a-z0-9_\.-]. This regular expression uses one lazy match, which is the curly braces ({2,6}). The curly braces are used to match the preceding token for a specific number of times. In this regular expression, the curly braces are used to match the preceding token, which is the character class [a-z\.], for a specific number of times, which is 2 to 6 times.

### Boundaries
Boundaries \b is one side of the word and the other side is not a word character ( a string or a space). Boundaries use \b and \B \b\ represents an anchor like caret \B\ This matches all positions where \b\ doesn’t match. In my regex expression above: no boundaries are used.

### Back-references
- [Introduction to regular expressions video](https://www.youtube.com/watch?v=7DG3kCDx53c)
- [Regular-Expressions.info](https://www.regular-expressions.info/)
- [MDN Web Docs - Regular-Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
- [3.ntu.edu - Regex](https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html)
- [Regular-Expressions101](https://regex101.com/)
- [Regex Tutorial: Matching a Username](https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial)
- [Regex cheatsheet](https://dev.to/catherinecodes/a-regex-cheatsheet-for-all-those-regex-haters-and-lovers--2cj1)
- [Regex101](https://regexone.com/)

### Look-ahead and Look-behind
Lookahead and lookbehind, collectively called “lookaround”, are zero-length assertions just like the start and end of line, and start and end of word anchors explained earlier in this tutorial. The difference is that lookaround actually matches characters, but then gives up the match, returning only the result: match or no match. That is why they are called “assertions”. They do not consume characters in the string, but only assert whether a match is possible or not.

## Author
This tutorial was written by Maninder Manan, a full stack web developer. My contact information is lised below for any questions or comments.

https://github.com/ManinderManan