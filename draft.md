# Matching a Hex Value: A Regex Tutorial

EXAMPLE DRAFT : This gist tutorial explains how to match a hex value as it relates to JavaScript. 

## Introductory Paragraph

* Explain the purpose of the tutorial. 

## Summary 

* A summary describing the regex featured in the tutorial which is focusing on hex values.
A regular expression (regex) is a jumble of characters that web developers use to perform "match checking" within strings. These are also used for searching and replacing things. Developers must search a pattern of characters and essentially translate what each one means. 

* Example: the following regex can be used to validate a hex value and verify that it is the correct hex value. 

## Table of Contents

* [Tutorial](#tutorial)
* [Hex Value Matching](#hex-value-matching)
* [About the Author](#about-the-author)

 ## Tutorial

### 
*  WHEN I read through each section of the tutorial, THEN I find a detailed explanation of what a specific component of the regex does
*  EACH section breaks down EACH COMPONENT of the regex AND EXPLAINS what it does for the hex value.

The forward slashes / denote the beginning and the end of a regex expression and will define a search pattern within JavaScript. Let's focus on the values between the forward slashes. 
^ symbol. For this hex value, the carat ^ indicates the start of the string or line. 

# symbol. The # sign is a token that matches a # character. (character code 35)
? symbol. This question mark (?) matches a number between 0 and 1 of the preceding token, which is #. 
() The parentheses groups multiple expressions together so as to extract a substring or use a back reference. 
[] Within the parentheses, there are square brackets. The square brackets contain a range of numbers (a-f) and/or case-sensitive letters (0-9). The brackets will match any single character in this range.
- The hyphen represents a range of letters or numbers in a square bracket.
{} The curly braces (in this particular case with the hex value) contain one number. This digit {n} indicates that that value inside the brackets [] occurs or matches exactly n times. 
| The pipe symbol stands for alternation. It behaves like a boolean (values of true or false). It matches the expression before or after the | symbol.
$ The dollar sign means "end." It matches the end of the string, in this case. 

### Search and Replace a Hex Value

Developers often need to search and replace values. 

* Who what when where why how
1. Define a search pattern using regex. Search and match the hex value as outlined in Hex Value Matching.
2. Replace the hex value with another hex value.


### Verifying the Hex Value

Sometimes developers need to check and verify a hex value. Here is how to do this.

* Who what when where why how
1. one
2. two
3. three


## About the Author

My name is Christy G. Hanson. I previously studied elementary education and marketing with a smidge of video game design before delving into full-stack web development via the University of Washington. I also experiment with both web design and content writing. My projects can be found on GitHub. Click [ChristyGHanson](https://github.com/ChristyGHanson) to view my profile.
