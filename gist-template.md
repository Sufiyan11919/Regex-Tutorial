# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Example

* Matching a Hex Value &ndash; `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

* Matching an Email &ndash; `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

* Matching a URL &ndash; `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

* Matching an HTML Tag &ndash; `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`

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

- a regular expression allows to search text in a string betweem / string / expression.
## Regex Components

### Anchors
- Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.
- For these matches, use the \A , \Z , and \z anchors (note that there is no \a anchor). The \A anchor ensures that a regex matches at the beginning of the string, while \Z and \z match at the end of the string. Once established the end points, via / we can use /string/ experssion anchors to filter any string or URL. The characters ^ and $ are our anchors. The ^ can be found at the beginning of the regex and the $ at the end. For eg: for Email validation

### Quantifiers
- Quantifiers limits the regex matches, there are be both minimum and maximum numbers of character searches
    For eg:- /ea/ :- this will search all the "ea" together present in the string but 
    if /ea+?/ :- this will search all the "e" present in the string and also additionally look for "ea". Basically "ea" will be optional

### OR Operator
- The symbol to use OR operator is "|", this performs a task to match either the left or right of the "|" symbol

### Character Classes
- There are basically two character classes. 
 i) \d :-  This searches for digits
 ii) \w:-  this searches for alphanumeric values
### Flags
- allows to matach multiple matches in string. if we choose #global flag, without global flag it will find only one match of string search in regular expression. i.e the first one. Global flag is match all and non global flag is only one match 
- Case insensitive - This will be case insensitive while searching

### Grouping and Capturing
- Grouping is a good when the string search is complicated. It partition regex with the help of (). This macthes only a particular portion of a string at a given time

### Bracket Expressions
- The symbol for Bracket expression is [ ]. In easy way it is any or all characters. It helps identify which portions of the expression can be any or all of the characters within the Brackets

for example mention above for URL:- the first bracket expression is looking for any digits, or any lower cased characters from a-z, or any "." or "-" & in the last two brackets, any or all the characters are been searched

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
