# RegexTutorial
This tutorial will explain what a Regex is and what it does. 

## Summary

Hello! Today I will help you understand what a "Matching an Email" Regex is, how it works, and what it can used it for!
This is the Matching an Email Regex code: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Cited Sites](#cited-sites)

## Regex Components

### Anchors

An Anchor is not matching any characters together but it is inserting the characters into the Regex for it to become a string or for matching. 
The Anchors for the email are ^ and $
the ^ if for stating the regex string.
The $ ends the regex string of the email to match.

### Quantifiers
The two quantifiers in the email regex code are + and {2, 6}.
The + is for matching the code to the left of the symbol.
For example... [a-z0-9_\.-]+ all the + is doing here is making sure that it matches what is inside of the [] (square brackets).
The {2, 6} is the [a-z\.] and can only be between 2-6 characters long for that last part of the code line.

### Grouping Constructs

There are three different groups that are in this email regex... 
The first group is ([a-z0-9_\.-]+) which is used for the users name. 
Then it's followed by the @ symbol. Now this is where group two comes in to play ([\da-z\.-]+) for what domain they are using. 
The third group is ([a-z\.]{2,6}) and that is for the top level domains like .com or .org!

### Bracket Expressions

 There are three bracket expressions... 
 The bracket expressions are telling us to match what rules are given inside of the brackets. 
[a-z0-9_\.-] is matching lowercase alphabet letters a-z, as well as numbers that are between 0-9, _ (underscores), . (periods), and (hyphens).
([\da-z\.-]+) is for matching. This can use multiple digits or one, alphabet letters a-z, . (periods), and - (hyphens).
[a-z\.] is matching for alphabet letters a-z.

### Character Classes

There is only one character class inside the email regex which is /d inside ([\da-z\.-]+). /d matches one digit only that's in the domain.

### Cited Sites

I used these two different sites to help me out with learning/explaining the email regex...:<br>
https://www.rexegg.com/regex-anchors.html<br>
https://www.keycdn.com/support/regex-cheat-sheet
