# regex-tutorial-gist
This is a gist for regex.

read readme for it and write.

Developers write code, but they also write about code. Take a moment to search the web for tutorials about any of the subjects you’ve learned so far in this course. You’re likely to find thousands of tutorials written by developers of all skill levels, but especially by junior developers—like you!

Your Challenge this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. You'll use the template provided in the starter code to create your tutorial.

# USER STORY
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines

# ACCEPTANCE CRITERIA
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile

watch the video before starting.
one of the simpler assignments.
how to create a gist and its URL.

Instead of creating a repository, you’ll publish a GitHub gist. GitHub describes a gist as a simple way to share code snippets with others. It’s also an ideal way to demonstrate a technique, teach a principle, or show off a solution. It functions just like a repository, and you’ll use Markdown to create it, just as you do with your READMEs. Gists can include code, images, links, and anything else you can include in a README.

After you’ve cloned the starter code, learn how to create a gistLinks to an external site.. You can also watch this video on how to use gistsLinks to an external site..

# BROOKE SAYS READ ALL OF IT.

What Is a Regex?
A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the @ symbol, followed by a domain.

Before you get started, watch this introduction to regular expressions videoLinks to an external site. and read Regex Tutorial: Matching a UsernameLinks to an external site. to learn how to identify the different components that make up a regex. If you need any additional help, there are many resources on the web. Feel free to do your own research to find one that can help you complete this assignment.

Once you have a better understanding of what these different parts of a regular expression do, you’ll need to explain what they do for a specific regex.

You can choose one of the following regular expressions or you can choose one that you found on your own (with the exception of the one that is covered in the Regex Tutorial: Matching a UsernameLinks to an external site.:

Matching a Hex Value – /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Matching a URL – /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

Matching an HTML Tag – /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/