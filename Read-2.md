# Text in HTML

Headings and paragraphs:

When creating a web page, we add tags
known as markup to the contents of the
page. These tags provide extra meaning
and allow browsers to show users the
appropriate structure for the page.


# Headings 

HTML has six levels of headings:

< h1 > is used for main headings

< h2 > is used for subheadings

If there are further sections
under the subheadings then the
< h3 > and < h4 > , < h5 > and < h6 > element is used



# Paragraph

To create a paragraph, surround
the words that make up the
paragraph with an opening < p >
tag and closing < /p > tag.

A paragraph consists of one or more sentences
that form a self-contained unit of discourse.



# CSS

CSS allows is to create rules that specify how the content of
an element should appear. For example, we can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.


CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.


CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.



# Example in CSS


< !DOCTYPE html >
< html >
< head >
< title >Introducing CSS< /title >
< link href="css/example.css" type="text/css"
rel="stylesheet" / >
< /head >
< body >
< h1 >From Garden to Plate< /h1 >
< p >A < i >potager< /i > is a French term for an
ornamental vegetable or kitchen garden ... < /p >
< h2 >What to Plant< /h2 >
< p >Plants are chosen as much for their functionality
as for their color and form ... < /p >
< /body >
< /html >
body {
font-family: Arial, Verdana, sans-serif;}
h1, h2 {
color: #ee3e80;}
p {
color: #665544;}




# Java Script 

Java script, it’s a programming language used both on the client side (Front-end) and server side (Back-end) that allows you to make web pages interactive


 # Java Script instructions 

 STATEMENTS: 

 1. A script is a series of instructions that a computer can follow one-by-one.Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

2. STATEMENTS ARE INSTRUCTIONS AND
EACH ONE STARTS ON A NEW LINE

3. STATEMENTS CAN BE ORGANIZED
INTO CODE BLOCKS

# COMMENTS

we should write comments to explain what code does.
They help make our code easier to read and understand.
This can help us and others who read your code.


# WHAT IS A VARIABLE?

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.

# DECISIONS AND LOOPS 


Scripts often need to behave differently depending upon how the user interacts with the web
page and/or the browser window itself. To determine which path to take, programmers often rely upon the following three concepts:

1. EVALUATIONS

2. DECISIONS 

3. LOOPS