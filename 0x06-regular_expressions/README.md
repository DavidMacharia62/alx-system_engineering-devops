# REGULAR EXPRESSIONS (REGEX/REGEXP)

Regular expressions, often abbreviated as regex or regexp, are powerful tools for pattern matching and manipulating text. They are widely used in programming and text processing to search, extract, and manipulate strings based on specific patterns.

In regular expressions, patterns are constructed using a combination of characters, metacharacters, and quantifiers. These patterns define a set of rules that match a specific sequence of characters within a larger text.

Here are some common metacharacters used in regular expressions:

1. `.` (dot): Matches any single character except a newline.
2. `*` (asterisk): Matches zero or more occurrences of the preceding character or group.
3. `+` (plus): Matches one or more occurrences of the preceding character or group.
4. `?` (question mark): Matches zero or one occurrence of the preceding character or group.
5. `[]` (square brackets): Defines a character class and matches any single character within the brackets.
6. `()` (parentheses): Groups characters or expressions together.
7. `|` (pipe): Acts as an OR operator, allowing multiple alternatives in a pattern.

Here are some examples of regular expression patterns and their usage:

1. `/a.b/`: Matches any string that has an "a" followed by any character and then a "b". For example, "acb", "aab", "axb".
2. `/a*b/`: Matches any string that has zero or more "a"s followed by a "b". For example, "b", "ab", "aaab".
3. `/ca+t/`: Matches any string that has a "c", followed by one or more "a"s, and then a "t". For example, "cat", "caaat", but not "ct".
4. `/colou?r/`: Matches both "color" and "colour", as the "u" is optional in the pattern.
5. `/[aeiou]/`: Matches any single vowel character.
6. `/^abc/`: Matches any string that starts with "abc".
7. `/abc|def/`: Matches either "abc" or "def" in a string.

Regular expressions are supported in many programming languages, text editors, and command-line tools. Each language or tool may have its own specific syntax or features related to regular expressions.
