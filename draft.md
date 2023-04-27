# Matching a Hex Value: A Regex Tutorial

This gist tutorial explains how to match a hex value using regex as it relates to JavaScript. 

## Introductory Paragraph

* Explain the purpose of the tutorial. 

## Summary 

* A summary describing the regex featured in the tutorial which is focusing on hex values.
A regular expression (regex) is a language of characters that web developers use to perform "match checking" within strings. These are also used for searching and replacing things. Developers must search a pattern of characters and essentially translate what each one means. 

* Example: the following regex can be used to validate a hex value and verify that it is the correct hex value. 

## Table of Contents

* [Tutorial in Hex Value Matching](#tutorial-in-hex-value-matching)
* [Forward Slashes](#forward-slashes)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Pipe Symbol](#the-pipe-symbol)
* [The Dollar Sign](#the-dollar-sign)
* [About the Author](#about-the-author)

## Tutorial in Hex Value Matching 

1. detailed explanation of what a specific component of the regex does
2. breaks down EACH COMPONENT of the regex by EXPLAINS what it does for the hex value.

### Forward Slashes (/)
* The forward slashes / denote the beginning and the end of a regex expression and will define a search pattern within JavaScript. Let's focus on the values between the forward slashes. 

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* ^ symbol. For this hex value, the carat ^ indicates the start of the string or line. 

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* (#) symbol. The # sign is a token that matches a # character. (character code 35)

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* ? symbol. This question mark (?) matches a number between 0 and 1 of the preceding token, which is #. 

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* () The parentheses groups multiple expressions together so as to extract a substring or use a back reference. 

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* [] Within the parentheses, there are square brackets. The square brackets contain a range of numbers (a-f) and/or case-sensitive letters (0-9). The brackets will match any single character in this range.

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* - The hyphen represents a range of letters or numbers in a square bracket.

| Example | Description |
|--------|-------------|
| asdf| asdf |

### 
* {} The curly braces (in this particular case with the hex value) contain one number. This digit {n} indicates that that value inside the brackets [] occurs or matches exactly n times. 

| Example | Description |
|--------|-------------|
| asdf| asdf |

### The Pipe Symbol (|)
The pipe symbol stands for alternation. 
* It behaves as a boolean (with a value of either "true" or "false"). It separates alternatives. 

| Example | Description |
|--------|-------------|
| gray\|grey | Matches either "gray" or "grey" |


### The Dollar Sign
* $ The dollar sign means "end." This symbol matches where a string ends, before a newline. 

| Example | Description |
|----|---|
| ^#?([a-f0-9]{6}\|[a-f0-9]{3})$ | $ indicates the end of the string. |

## About the Author

My name is Christy G. Hanson. I previously studied elementary education and marketing with a smidge of video game design before delving into full-stack web development via the University of Washington. I also experiment with both web design and content writing. My projects can be found on GitHub. Click [ChristyGHanson](https://github.com/ChristyGHanson) to view my profile.
