# Regex Tutorial Jerry Sparling

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

The matching of a hex value is the regex that I will be covering. One example of matching a hex code is: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ there are different sections that I will be breaking down later. 

## Table of Contents

- [Regex Tutorial Jerry Sparling](#regex-tutorial-jerry-sparling)
  - [Summary](#summary)
  - [Table of Contents](#table-of-contents)
  - [Regex Components](#regex-components)
    - [Anchors](#anchors)
    - [Quantifiers](#quantifiers)
    - [Grouping Constructs](#grouping-constructs)
    - [Bracket Expressions](#bracket-expressions)
    - [Character Classes](#character-classes)
    - [The OR Operator](#the-or-operator)
    - [Flags](#flags)
    - [Character Escapes](#character-escapes)
  - [Author](#author)

## Regex Components

### Anchors
Anchors are the characters that indicate the start and stop of the text. In our example /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ the ^ and $ are the start and stop anchors.
### Quantifiers
Quantifiers are the numbers inside the curly braces that indicates how many times the value before is gone through. Referring to the example once more the [a-f0-9]{6} part is searching for a series of characters ranging from a-f and 0-9 a total of six times. Similarly we see it again for the [a-f0-9]{3} which is doing the same thing except it is only searching for 3 characters this time.
### Grouping Constructs
The Grouping Constructs are the parts inside the brackets. ([a-f0-9]{6}|[a-f0-9]{3}) is a grouping construct that searches those specific characters. Looking at our example /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ notice the two grouping constructs are grouped together inside of () and a vertical line is separating them, this means it searches for both sets and will only return when both are satisfied.
### Bracket Expressions
Bracket expressions are the part that involves the [a-f0-9]. It will range from a through f and 0 through 9.
### Character Classes
Character classes are predetermined bracket expressions. It is a way to write the same thing without having to write everything out by hand. Our example doesn't have character classes.
### The OR Operator
The OR operator is the operator that is represented as |. In our example we see the OR operator separating the expressions /^#?([a-f0-9]{6}|[a-f0-9]{3})$/. It is simply looking for [a-f0-9] 6 or 3 times.
### Flags
Flags are additional parameters that are optional that affects the way it searches. In the example we see #, ?. The ? flag makes the # character optional. 
### Character Escapes
The backslash"\" is commonly used to escape a character. Those characters include .*+?^$[](){}| which have a special meaning if they are escaped. 
## Author
I am Jerry Sparling, a student at EdX KU coding boot camp.
<br/>
GitHub: https://github.com/Jrsparling
