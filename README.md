# regex-tutorial-gist

* create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. 
* You'll use the template provided in the starter code to create your tutorial.

# USER STORY
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines

how to create a gist and its URL.

Instead of creating a repository, you’ll publish a GitHub gist. GitHub describes a gist as a simple way to share code snippets with others. It’s also an ideal way to demonstrate a technique, teach a principle, or show off a solution. It functions just like a repository, and you’ll use Markdown to create it, just as you do with your READMEs. Gists can include code, images, links, and anything else you can include in a README.

* After you’ve cloned the starter code, learn how to create a gist
* You can also watch this video on how to use gists

## What Is a Regex?
* A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

* For example, the following regular expression can be used to verify that user input is a valid email address:

 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

* Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the @ symbol, followed by a domain.

* Before you get started, watch this introduction to regular expressions video and read Regex Tutorial: Matching a Username to learn how to identify the different components that make up a regex.

Once you have a better understanding of what these different parts of a regular expression do, you’ll need to explain what they do for a specific regex.
 
Matching a Hex Value 
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

The forward slashes / denote the beginning and the end of the regex expression. Let's focus on the values between the forward slashes. 

^ symbol. For this hex value, the carat ^ indicates the start of the string or line. 
# symbol. The # sign is a token that matches a # character. (character code 35)
? symbol. This question mark (?) matches a number between 0 and 1 of the preceding token, which is #. 
() The parentheses groups multiple expressions together so as to extract a substring or use a back reference. 
[] Within the parentheses, there are square brackets. The square brackets contain a range of numbers (a-f) and/or case-sensitive letters (0-9). The brackets will match any single character in this range.
- The hyphen represents a range of letters or numbers in a square bracket.
{} The curly braces (in this particular case with the hex value) contain one number. This digit {n} indicates that that value inside the brackets [] occurs or matches exactly n times. 
| The pipe symbol stands for alternation. It behaves like a boolean (values of true or false). It matches the expression before or after the | symbol.
$ The dollar sign means "end." It matches the end of the string, in this case. 

Let's explore regex quantifiers.
[]{n} The value in the brackets occurs n times.
[a-f0-9]{6} This number inside the bracket occurs 6 times. 
[a-f0-9]{3} This number in the brackets occurs 3 times.


