---
layout: lesson
title: Regular Expressions
root: .
---
###Using text editors in conjunction with Excel.
- Good text editors (Text Wrangler, Notepad++) can transform line endings for you if you have trouble importing a saved document.
- Copy and paste to remove functions and keep values.
- Some things are just easier to do in text editors.

## What are regular expressions?
- Fancy search and replace using strings. Can be relatively simple if you know a few basic rules.

## Exercises
1. Open the grid11.txt file in your text editor
2. Turn on invisibles.
3. Remove all empty lines (^\n)
4. Flip long and lat.

### Basic matching
> Wildcards: *.txt (finds any thing with a .txt ending)

> \w = a word character [A-Za-z0-9_]

> \t = a tab character

> \s = a whitespace character that matches a space, a tab, a line break, or a form feed.

> \S = a non-whitespace character.

> \r \n = an end of line character.

> \d = a digit from 0-9.

### Anchors

> ^ = The match must start at the beginning of the string or line.

> $ = The match must occur at the end of the string or before \n at the end of the line or string.

### Quantifiers

> {} = [\d{3}] Match any 3 decimal digits.

> + = makes it greedy

> . = any letter, number or symbiol except end of line characters. Same as saying "add one character".

### Character Groups

> [] = defines a character group

> [^aeiou] = everything but what is in the character group





[answers: (^\S+)(.)(-\S+); $3$2$1]






Previous: [Functions.](08-functions.html)
Next: [iDigBio Portal](09-iDigBio-portal.html)