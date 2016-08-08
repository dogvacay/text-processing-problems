Text Processing Problems
========================

Please provide a solution in Java that meets the requirements of problems described below. Java 1.7 is preferred for now. Though if you wish to use Java 1.8, and use 1.8 features, please provide at least one solution that does not require 1.8 features. Document any assumptions you are making about inputs and outputs clearly. 

Make the best programming choices as you would normally do for this assignment. The you'll be evaluated on your proficiency with the Java language, programming and design skills, pursuit of best practices, accuracy of solution, and code testability. 

The tests that prove your solutions work are a necessary deliverable given we want proof the solution works. 

Once you are ready with the solution, please zip the source set and share it via email. A short summary of your approach is welcome documentation. Good luck !

## FIRST PROBLEM

1: Keyword highlighting
-----------------------
* _Given_: A textual payload for input processing and a library of keywords
* _When_: A keyword is encountered in the textual payload as a word
* _Then_: The keyword should be highlighted by place a "<" before the keyword and a ">" after the keyword

E.g.
* _Keyword_: "Red"
* _Input_: "A Red Sky"
* _Output_: "A \<Red\> Sky"  

* _Input_: "I come from Redmond California"
* _Output_: "I come from Redmond California"  

Use this README file as your input text. Select all, copy, paste.

Use this list as your keywords: java, snippet, solution

## PROBLEM TWO

2: Snippet extraction
---------------------
A snippet of text is an arbitray length of text pulled out from a larger body of text. A piece of text. An extract of text.

We want you to find keywords in text, and extract the snippet of text that surrounds it. Use the code you wrote in problem one to find and highlight the keyword in the snippet.

In our problem a snippet represents text up to 20 characters preceding the keyword, the keyword itself, and up to 20 characters following the keyword. Our problem then is:

* _Given_: A textual payload for input processing and a library of keywords
* _When_: A keyword is encountered in the textual payload as a word
* _Then_: A snippet of text (as decribed above) surrounding the keyword is extracted and the keyword highlighted

Example: 
* _Keyword_: refers
* _Input Text_: "This is some sample text that I am typing. Typing refers back to the days of typewriters." 
* _Output Snippet_: "I am typing. Typing \<refers\> back to the days of"


Use this README as your input text (select, copy, paste)

Use this list as your keywords: java, snippet, solution
