# Title (URL Tutorial)
 
## Itroductory Paragraph:
I will be describing the different parts of the following regex code:
(/^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])

## Summary:
this particular regex code is used to match a URL to make sure it is correct.
(/^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])/?$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Character Classes](#character-classes)
- [Author](#author)

## Regex Components

### Anchors
This code includes the anchors:

^, $

The ^ matches the beginning of the string, or the beginning of al ine if the multiline flag is enabled.

The $ matches the end of the string, or the end of a line if the multiline flag is enabled.


### Quantifiers
This code includes the following quantifier:

?, +, {2,6}, *

The ? matches 0 or 1 of the preceding token, effectively making it optional.

The + matches 1 or more of the preceding token(s).

The {2,6} matches the specified quantity of the previous token. {2} will match exactly 2. {2,} will match 2 or more.

The * matches 0 or more of the preceding token.


### Grouping Constructs
This code includes many capturing groups:

(https?://), ([\da-z.-]+), ([a-z.]{2,6}), ([/\w .-]*)

Capturing groups multiple tokens together and creates a capture group for extracting a substring or using a backreference.


### Character Classes
This code includes character classes:

\d, a-z, \w

The \d stands for Digit. It is used to match and digit character(0-9). Equivalent to [0-9].

The a-z is a Range. It matches a character having a character code between the two specified characters inclusive.

The \w stands for Word. It matches any word character (alphanumeric & underscore). Only matches low-ascii characters (no accented or non-roman characters). Equivalent to [A-Aa-z0-9_]



## Author

Shaima Jobran 
[Github Link](https://github.com/shaimajobran)


