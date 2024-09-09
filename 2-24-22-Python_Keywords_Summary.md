## USER
Analyze and provide the most important python terms and keywords mentioned within the article https://blog.finxter.com/python-cheat-sheet/

## ASSISTANT
The article from Finxter is a Python cheat sheet aimed at beginners. It covers a range of Python keywords and terms that are essential for anyone starting out with the language. Below are some of the most important Python terms and keywords mentioned in the article:

### Python Keywords

1. **False, True**: Data values from the Boolean data type.
   - Example: `False == (1 > 2), True == (2 > 1)`

2. **and, or, not**: Logical operators.
   - Example: `(x and y)`, `(x or y)`, `(not x)`

3. **break**: Ends loop prematurely.
   - Example: `while(True): break`

4. **continue**: Finishes the current loop iteration.
   - Example: `while(True): continue`

5. **class**: Defines a new class for object-oriented programming.
   - Example: 
     ```python
     class Beer:
       def __init__(self):
         self.content = 1.0
       def drink(self):
         self.content = 0.0
     ```

6. **def**: Defines a new function or class method.
   - Example: `def incrementor(x): return x + 1`

7. **if, elif, else**: Conditional program execution.
   - Example: 
     ```python
     x = int(input("your value: "))
     if x > 3:
       print("Big")
     elif x == 3:
       print("Medium")
     else:
       print("Small")
     ```

8. **for, while**: Repeated execution of loop body.
   - Example: `for i in [0,1,2]: print(i)`

9. **in**: Checks whether an element is in a sequence.
   - Example: `42 in [2, 39, 42]`

10. **is**: Checks whether both elements point to the same object.
    - Example: `y = x = 3, x is y`

11. **None**: Represents an empty value constant.
    - Example: `def f(): x = 2, f() is None`

12. **lambda**: Anonymous function.
    - Example: `(lambda x: x + 3)(3)`

13. **return**: Terminates execution of the function and passes the flow of execution to the caller.
    - Example: `def incrementor(x): return x + 1`

These keywords are fundamental to Python programming and understanding them can provide a strong foundation for further learning. The article also includes interactive puzzles and exercises to help reinforce the understanding of these keywords.

## USER
Read and summarize the text https://greenteapress.com/thinkpython/html/index.html

## ASSISTANT
It appears that the URL provided does not contain the text of the book "Think Python" but rather a page with options to contribute and a list of other books like "Think Bayes," "Think Stats," and "Think Complexity." There is no content to summarize from this specific URL. Would you like to know more about the "Think Python" book in general?

## USER
Summarize the text from a pdf

## ASSISTANT
Certainly! Please provide the URL of the PDF you would like summarized.

## USER
file:///Users/jookburleson/Desktop/Allen%20B.%20Downey%20-%20Think%20Python,%202nd%20Edition_%20How%20to%20Think%20Like%20a%20Computer%20Scientist%20(2015,%20O'Reilly%20Media)%20-%20libgen.lc.pdf

## ASSISTANT
I'm sorry, I can't access files from your local machine directly. However, you can upload the PDF to a publicly accessible location like Google Drive or Dropbox and then share the URL with me. Would you like to proceed that way?

## USER
yes

## ASSISTANT
Great! Once you've uploaded the PDF to a publicly accessible location like Google Drive or Dropbox, please share the URL with me. Then I'll be able to read and summarize the text for you.

## USER
Act like a document/text loader until you load and remember the content of the next text/s or document/s.
There might be multiple files, each file is marked by name in the format ### DOCUMENT NAME.
I will send them to you in chunks. Each chunk starts will be noted as [START CHUNK x/TOTAL], and the end of this chunk will be noted as [END CHUNK x/TOTAL], where x is the number of current chunks, and TOTAL is the number of all chunks I will send you.
I will split the message in chunks, and send them to you one by one. For each message follow the instructions at the end of the message.
Let's begin:

[START CHUNK 1/2]
Provide a comprehensive and digestible summary of this chapter The goal of this book is to teach you to think like a computer scientist. This way of thinking combines some of the best features of mathematics, engineering, and natural science. Like mathematicians, computer scientists use formal languages to denote ideas (specifically computations). Like engineers, they design things, assembling components into systems and evaluating tradeoffs among alternatives. Like scientists, they observe the behavior of complex systems, form hypotheses, and test predictions.
The single most important skill for a computer scientist is problem solving. Problem solving means the ability to formulate problems, think creatively about solutions, and express a solution clearly and accurately. As it turns out, the process of learning to program is an excellent opportunity to practice problem-solving skills. That’s why this chapter is called “The Way of the Program”.
On one level, you will be learning to program, a useful skill by itself. On another level, you will use programming as a means to an end. As we go along, that end will become clearer.
What Is a Program?
A program is a sequence of instructions that specifies how to perform a computation. The computation might be something mathematical, such as solving a system of equations or finding the roots of a polynomial, but it can also be a symbolic computa‐ tion, such as searching and replacing text in a document or something graphical, like processing an image or playing a video.
The details look different in different languages, but a few basic instructions appear in just about every language:
 www.it-ebooks.info
1
input:
Get data from the keyboard, a file, the network, or some other device.
output:
Display data on the screen, save it in a file, send it over the network, etc.
math:
Perform basic mathematical operations like addition and multiplication.
conditional execution:
Check for certain conditions and run the appropriate code.
repetition:
Perform some action repeatedly, usually with some variation.
Believe it or not, that’s pretty much all there is to it. Every program you’ve ever used, no matter how complicated, is made up of instructions that look pretty much like these. So you can think of programming as the process of breaking a large, complex task into smaller and smaller subtasks until the subtasks are simple enough to be per‐ formed with one of these basic instructions.
Running Python
One of the challenges of getting started with Python is that you might have to install Python and related software on your computer. If you are familiar with your operat‐ ing system, and especially if you are comfortable with the command-line interface, you will have no trouble installing Python. But for beginners, it can be painful to learn about system administration and programming at the same time.
To avoid that problem, I recommend that you start out running Python in a browser. Later, when you are comfortable with Python, I’ll make suggestions for installing Python on your computer.
There are a number of web pages you can use to run Python. If you already have a favorite, go ahead and use it. Otherwise I recommend PythonAnywhere. I provide detailed instructions for getting started at http://tinyurl.com/thinkpython2e.
There are two versions of Python, called Python 2 and Python 3. They are very simi‐ lar, so if you learn one, it is easy to switch to the other. In fact, there are only a few differences you will encounter as a beginner. This book is written for Python 3, but I include some notes about Python 2.
The Python interpreter is a program that reads and executes Python code. Depend‐ ing on your environment, you might start the interpreter by clicking on an icon, or by typing python on a command line. When it starts, you should see output like this:
 2 | Chapter 1: The Way of the Program
www.it-ebooks.info

    Python 3.4.0 (default, Jun 19 2015, 14:20:21)
    [GCC 4.8.2] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>>
The first three lines contain information about the interpreter and the operating sys‐ tem it’s running on, so it might be different for you. But you should check that the version number, which is 3.4.0 in this example, begins with 3, which indicates that you are running Python 3. If it begins with 2, you are running (you guessed it) Python 2.
The last line is a prompt that indicates that the interpreter is ready for you to enter code. If you type a line of code and hit Enter, the interpreter displays the result:
>>> 1 + 1 2
Now you’re ready to get started. From here on, I assume that you know how to start the Python interpreter and run code.
The First Program
Traditionally, the first program you write in a new language is called “Hello, World!” because all it does is display the words “Hello, World!” In Python, it looks like this:
    >>> print('Hello, World!')
This is an example of a print statement, although it doesn’t actually print anything on paper. It displays a result on the screen. In this case, the result is the words
    Hello, World!
The quotation marks in the program mark the beginning and end of the text to be displayed; they don’t appear in the result.
The parentheses indicate that print is a function. We’ll get to functions in Chapter 3. In Python 2, the print statement is slightly different; it is not a function, so it doesn’t
use parentheses.
    >>> print 'Hello, World!'
This distinction will make more sense soon, but that’s enough to get started.
Arithmetic Operators
After “Hello, World”, the next step is arithmetic. Python provides operators, which are special symbols that represent computations like addition and multiplication.
The operators +, -, and * perform addition, subtraction, and multiplication, as in the following examples:
 www.it-ebooks.info
The First Program | 3

    >>> 40 + 2
    42
    >>> 43 - 1
    42
>>> 6 * 7 42
The operator / performs division: >>> 84 / 2
42.0
You might wonder why the result is 42.0 instead of 42. I’ll explain in the next section.
Finally, the operator ** performs exponentiation; that is, it raises a number to a power:
>>> 6**2 + 6 42
In some other languages, ^ is used for exponentiation, but in Python it is a bitwise operator called XOR. If you are not familiar with bitwise operators, the result will surprise you:
>>> 6 ^ 2 4
I won’t cover bitwise operators in this book, but you can read about them at http:// wiki.python.org/moin/BitwiseOperators.
Values and Types
A value is one of the basic things a program works with, like a letter or a number. Some values we have seen so far are 2, 42.0, and 'Hello, World!'
These values belong to different types: 2 is an integer, 42.0 is a floating-point num‐ ber, and 'Hello, World!' is a string, so-called because the letters it contains are strung together.
If you are not sure what type a value has, the interpreter can tell you:
    >>> type(2)
    <class 'int'>
    >>> type(42.0)
    <class 'float'>
    >>> type('Hello, World!')
    <class 'str'>
In these results, the word “class” is used in the sense of a category; a type is a category of values.
 4 | Chapter 1: The Way of the Program
www.it-ebooks.info

Not surprisingly, integers belong to the type int, strings belong to str, and floating- point numbers belong to float.
What about values like '2' and '42.0'? They look like numbers, but they are in quo‐ tation marks like strings:
    >>> type('2')
    <class 'str'>
    >>> type('42.0')
    <class 'str'>
They’re strings.
When you type a large integer, you might be tempted to use commas between groups
of digits, as in 1,000,000. This is not a legal integer in Python, but it is legal: >>> 1,000,000
(1, 0, 0)
That’s not what we expected at all! Python interprets 1,000,000 as a comma-
separated sequence of integers. We’ll learn more about this kind of sequence later.
Formal and Natural Languages
Natural languages are the languages people speak, such as English, 
[END CHUNK 1/2]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 1/2]

## USER
[START CHUNK 2/2]
Spanish, and French. They were not designed by people (although people try to impose some order on them); they evolved naturally.
Formal languages are languages that are designed by people for specific applications. For example, the notation that mathematicians use is a formal language that is partic‐ ularly good at denoting relationships among numbers and symbols. Chemists use a formal language to represent the chemical structure of molecules. And most impor‐ tantly:
Programming languages are formal languages that have been designed to express computations.
Formal languages tend to have strict syntax rules that govern the structure of state‐ ments. For example, in mathematics the statement 3 + 3 = 6 has correct syntax, but 3 + = 3$6 does not. In chemistry H2O is a syntactically correct formula, but 2Zz is not.
Syntax rules come in two flavors, pertaining to tokens and structure. Tokens are the basic elements of the language, such as words, numbers, and chemical elements. One of the problems with 3 + = 3$6 is that $ is not a legal token in mathematics (at least as far as I know). Similarly, 2Zz is not legal because there is no element with the abbreviation Zz.
 www.it-ebooks.info
Formal and Natural Languages | 5

The second type of syntax rule pertains to the way tokens are combined. The equa‐ tion 3 + = 3 is illegal because even though + and = are legal tokens, you can’t have one right after the other. Similarly, in a chemical formula the subscript comes after the element name, not before.
This is @ well-structured Engli$h sentence with invalid t*kens in it. This sentence all valid tokens has, but invalid structure with.
When you read a sentence in English or a statement in a formal language, you have to figure out the structure (although in a natural language you do this subconsciously). This process is called parsing.
Although formal and natural languages have many features in common—tokens, structure, and syntax—there are some differences:
ambiguity:
Natural languages are full of ambiguity, which people deal with by using contex‐ tual clues and other information. Formal languages are designed to be nearly or completely unambiguous, which means that any statement has exactly one mean‐ ing, regardless of context.
redundancy:
In order to make up for ambiguity and reduce misunderstandings, natural lan‐ guages employ lots of redundancy. As a result, they are often verbose. Formal languages are less redundant and more concise.
literalness:
Natural languages are full of idiom and metaphor. If I say, “The penny dropped”, there is probably no penny and nothing dropping (this idiom means that some‐ one understood something after a period of confusion). Formal languages mean exactly what they say.
Because we all grow up speaking natural languages, it is sometimes hard to adjust to formal languages. The difference between formal and natural language is like the dif‐ ference between poetry and prose, but more so:
Poetry:
Words are used for their sounds as well as for their meaning, and the whole poem together creates an effect or emotional response. Ambiguity is not only common but often deliberate.
Prose:
The literal meaning of words is more important, and the structure contributes more meaning. Prose is more amenable to analysis than poetry but still often ambiguous.
 6 | Chapter 1: The Way of the Program
www.it-ebooks.info
[END CHUNK 2/2]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 2/2]

## USER
Please continue

## ASSISTANT
Certainly! Here's a comprehensive and digestible summary of the chapter:

### The Way of the Program

#### Goal
The chapter aims to teach the reader to think like a computer scientist, a mindset that combines elements of mathematics, engineering, and natural science. The most crucial skill for a computer scientist is problem-solving, which involves formulating problems and thinking creatively about solutions.

#### What is a Program?
A program is a sequence of instructions for performing a computation. These computations can be mathematical, symbolic, or graphical. The basic instructions in almost every programming language include input, output, math operations, conditional execution, and repetition.

#### Running Python
The chapter suggests starting with Python in a browser for beginners to avoid the complexities of system administration. Python 2 and Python 3 are similar, but the book focuses on Python 3.

#### The First Program
The first program traditionally written in a new language is "Hello, World!" In Python, it's executed using the `print` function.

#### Arithmetic Operators
Python provides operators for basic arithmetic operations like addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).

#### Values and Types
Values in Python belong to different types like integers (`int`), floating-point numbers (`float`), and strings (`str`).

#### Formal and Natural Languages
Programming languages are formal languages with strict syntax rules. Unlike natural languages, which can be ambiguous and full of idioms, formal languages are designed to be unambiguous and literal.

#### Key Takeaways
- Programming is about breaking down complex tasks into simpler subtasks.
- Formal languages, like programming languages, are less ambiguous than natural languages.
- Learning to program is an excellent way to practice problem-solving skills.

The chapter serves as an introduction to programming and Python, covering the basics that every beginner should know.

## USER
please provide a comprehensive and digestible summary of this bulky text

## ASSISTANT
Certainly! Here's a more concise summary of the chapter:

### Summary: The Way of the Program

#### Objective
The chapter aims to instill the mindset of a computer scientist, emphasizing problem-solving as the core skill. It serves as an introduction to programming using Python.

#### Key Concepts

- **Program**: A set of

## USER
Act like a document/text loader until you load and remember the content of the next text/s or document/s.
There might be multiple files, each file is marked by name in the format ### DOCUMENT NAME.
I will send them to you in chunks. Each chunk starts will be noted as [START CHUNK x/TOTAL], and the end of this chunk will be noted as [END CHUNK x/TOTAL], where x is the number of current chunks, and TOTAL is the number of all chunks I will send you.
I will split the message in chunks, and send them to you one by one. For each message follow the instructions at the end of the message.
Let's begin:

[START CHUNK 1/7]
The Strange History of This Book
In January 1999 I was preparing to teach an introductory programming class in Java.
I had taught it three times and I was getting frustrated. The failure rate in the class
was too high and, even for students who succeeded, the overall level of achievement
was too low.
One of the problems I saw was the books. They were too big, with too much unneces‐
sary detail about Java, and not enough high-level guidance about how to program.
And they all suffered from the trapdoor effect: they would start out easy, proceed
gradually, and then somewhere around Chapter 5 the bottom would fall out. The stu‐
dents would get too much new material, too fast, and I would spend the rest of the
semester picking up the pieces.
Two weeks before the first day of classes, I decided to write my own book. My goals
were:
• Keep it short. It is better for students to read 10 pages than not read 50 pages.
• Be careful with vocabulary. I tried to minimize jargon and define each term at
first use.
• Build gradually. To avoid trapdoors, I took the most difficult topics and split
them into a series of small steps.
• Focus on programming, not the programming language. I included the mini‐
mum useful subset of Java and left out the rest.
I needed a title, so on a whim I chose How to ink Like a Computer Scientist.
My first version was rough, but it worked. Students did the reading, and they under‐
stood enough that I could spend class time on the hard topics, the interesting topics
and (most important) letting the students practice.
xi
www.it-ebooks.info
I released the book under the GNU Free Documentation License, which allows users
to copy, modify, and distribute the book.
What happened next is the cool part. Jeff Elkner, a high school teacher in Virginia,
adopted my book and translated it into Python. He sent me a copy of his translation,
and I had the unusual experience of learning Python by reading my own book. As
Green Tea Press, I published the first Python version in 2001.
In 2003 I started teaching at Olin College and I got to teach Python for the first time.
The contrast with Java was striking. Students struggled less, learned more, worked on
more interesting projects, and generally had a lot more fun.
Since then I’ve continued to develop the book, correcting errors, improving some of
the examples and adding material, especially exercises.
The result is this book, now with the less grandiose title ink Python. Some of the
changes are:
• I added a section about debugging at the end of each chapter. These sections
present general techniques for finding and avoiding bugs, and warnings about
Python pitfalls.
• I added more exercises, ranging from short tests of understanding to a few sub‐
stantial projects. Most exercises include a link to my solution.
• I added a series of case studies—longer examples with exercises, solutions, and
discussion.
• I expanded the discussion of program development plans and basic design
patterns.
• I added appendices about debugging and analysis of algorithms.
The second edition of ink Python has these new features:
• The book and all supporting code have been updated to Python 3.
• I added a few sections, and more details on the Web, to help beginners get started
running Python in a browser, so you don’t have to deal with installing Python
until you want to.
• For “The turtle Module” on page 35 I switched from my own turtle graphics
package, called Swampy, to a more standard Python module, turtle, which is
easier to install and more powerful.
• I added a new chapter called “The Goodies”, which introduces some additional
Python features that are not strictly necessary, but sometimes handy.
xii | Preface
www.it-ebooks.info
I hope you enjoy working with this book, and that it helps you learn to program and
think like a computer scientist, at least a little bit.
—Allen B. Downey
Olin College
Conventions Used in This Book
The following typographical conventions are used in this book:
Italic
Indicates new terms, URLs, email addresses, filenames, and file extensions.
Bold
Indicates terms defined in the Glossary.
Constant width
Used for program listings, as well as within paragraphs to refer to program ele‐
ments such as variable or function names, databases, data types, environment
variables, statements, and keywords.
Constant width bold
Shows commands or other text that should be typed literally by the user.
Constant width italic
Shows text that should be replaced with user-supplied values or by values deter‐
mined by context.
Using Code Examples
Supplemental material (code examples, exercises, etc.) is available for download at
http://www.greenteapress.com/thinkpython2/code.
This book is here to help you get your job done. In general, if example code is offered
with this book, you may use it in your programs and documentation. You do not
need to contact us for permission unless you’re reproducing a significant portion of
the code. For example, writing a program that uses several chunks of code from this
book does not require permission. Selling or distributing a CD-ROM of examples
from O’Reilly books does require permission. Answering a question by citing this
book and quoting example code does not require permission. Incorporating a signifi‐
cant amount of example code from this book into your product’s documentation does
require permission.
We appreciate, but do not require, attribution. An attribution usually includes the
title, author, publisher, and ISBN. For example: “ink Python, 2nd Edition, by Allen
B. Downey (O’Reilly). Copyright 2016 Allen Downey, 978-1-4919-3936-9.”
Preface | xiii
www.it-ebooks.info
If you feel your use of code examples falls outside fair use or the permission given
above, feel free to contact us at permissions@oreilly.com.
Safari® Books Online
Safari Books Online (www.safaribooksonline.com) is an ondemand digital library that delivers expert content in both
book and video form from the world’s leading authors in tech‐
nology and business.
Technology professionals, software developers, web designers, and business and crea‐
tive professionals use Safari Books Online as their primary resource for research,
problem solving, learning, and certification training.
Safari Books Online offers a range of plans and pricing for enterprise, government,
and education, and individuals.
Members have access to thousands of books, training videos, and prepublication
manuscripts in one fully searchable database from publishers like O’Reilly Media,
Prentice Hall Professional, Addison-Wesley Professional, Microsoft Press, Sams, Que,
Peachpit Press, Focal Press, Cisco Press, John Wiley & Sons, Syngress, Morgan Kauf‐
mann, IBM Redbooks, Packt, Adobe Press, FT Press, Apress, Manning, New Riders,
McGraw-Hill, Jones & Bartlett, Course Technology, and hundreds more. For more
information about Safari Books Online, please visit us online.
How to Contact Us
Please address comments and questions concerning this book to the publisher:
O’Reilly Media, Inc.
1005 Gravenstein Highway North
Sebastopol, CA 95472
800-998-9938 (in the United States or Canada)
707-829-0515 (international or local)
707-829-0104 (fax)
We have a web page for this book, where we list errata, examples, and any additional
information. You can access this page at http://bit.ly/think-python_2E.
To comment or ask technical questions about this book, send email to bookques‐
tions@oreilly.com.
For more information about our books, courses, conferences, and news, see our web‐
site at http://www.oreilly.com.
xiv | Preface
www.it-ebooks.info
Find us on Facebook: http://facebook.com/oreilly
Follow us on Twitter: http://twitter.com/oreillymedia
Watch us on YouTube: http://www.youtube.com/oreillymedia
Acknowledgments
Many thanks to Jeff Elkner, who translated my Java book into Python, which got this
project started and introduced me to what has turned out to be my favorite language.
Thanks also to Chris Meyers, who contributed several sections to How to ink Like 
[END CHUNK 1/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 1/7]

## USER
[START CHUNK 2/7]
a
Computer Scientist.
Thanks to the Free Software Foundation for developing the GNU Free Documenta‐
tion License, which helped make my collaboration with Jeff and Chris possible, and
Creative Commons for the license I am using now.
Thanks to the editors at Lulu who worked on How to ink Like a Computer Scientist.
Thanks to the editors at O’Reilly Media who worked on ink Python.
Thanks to all the students who worked with earlier versions of this book and all the
contributors (listed below) who sent in corrections and suggestions.
Contributor List
More than 100 sharp-eyed and thoughtful readers have sent in suggestions and cor‐
rections over the past few years. Their contributions, and enthusiasm for this project,
have been a huge help.
If you have a suggestion or correction, please send email to feedback@thinkpy‐
thon.com. If I make a change based on your feedback, I will add you to the contribu‐
tor list (unless you ask to be omitted).
If you include at least part of the sentence the error appears in, that makes it easy for
me to search. Page and section numbers are fine, too, but not quite as easy to work
with. Thanks!
• Lloyd Hugh Allen sent in a correction to Section 8.4.
• Yvon Boulianne sent in a correction of a semantic error in Chapter 5.
• Fred Bremmer submitted a correction in Section 2.1.
• Jonah Cohen wrote the Perl scripts to convert the LaTeX source for this book into beauti‐
ful HTML.
• Michael Conlon sent in a grammar correction in Chapter 2 and an improvement in style
in Chapter 1, and he initiated discussion on the technical aspects of interpreters.
• Benoit Girard sent in a correction to a humorous mistake in Section 5.6.
Preface | xv
www.it-ebooks.info
• Courtney Gleason and Katherine Smith wrote horsebet.py, which was used as a case
study in an earlier version of the book. Their program can now be found on the website.
• Lee Harr submitted more corrections than we have room to list here, and indeed he
should be listed as one of the principal editors of the text.
• James Kaylin is a student using the text. He has submitted numerous corrections.
• David Kershaw fixed the broken catTwice function in Section 3.10.
• Eddie Lam has sent in numerous corrections to Chapters 1, 2, and 3. He also fixed the
Makefile so that it creates an index the first time it is run and helped us set up a version‐
ing scheme.
• Man-Yong Lee sent in a correction to the example code in Section 2.4.
• David Mayo pointed out that the word “unconsciously” in Chapter 1 needed to be
changed to “subconsciously”.
• Chris McAloon sent in several corrections to Sections 3.9 and 3.10.
• Matthew J. Moelter has been a long-time contributor who sent in numerous corrections
and suggestions to the book.
• Simon Dicon Montford reported a missing function definition and several typos in Chap‐
ter 3. He also found errors in the increment function in Chapter 13.
• John Ouzts corrected the definition of “return value” in Chapter 3.
• Kevin Parks sent in valuable comments and suggestions as to how to improve the distri‐
bution of the book.
• David Pool sent in a typo in the glossary of Chapter 1, as well as kind words of encourage‐
ment.
• Michael Schmitt sent in a correction to the chapter on files and exceptions.
• Robin Shaw pointed out an error in Section 13.1, where the printTime function was used
in an example without being defined.
• Paul Sleigh found an error in Chapter 7 and a bug in Jonah Cohen’s Perl script that gener‐
ates HTML from LaTeX.
• Craig T. Snydal is testing the text in a course at Drew University. He has contributed sev‐
eral valuable suggestions and corrections.
• Ian Thomas and his students are using the text in a programming course. They are the
first ones to test the chapters in the latter half of the book, and they have made numerous
corrections and suggestions.
• Keith Verheyden sent in a correction in Chapter 3.
• Peter Winstanley let us know about a longstanding error in our Latin in Chapter 3.
• Chris Wrobel made corrections to the code in the chapter on file I/O and exceptions.
• Moshe Zadka has made invaluable contributions to this project. In addition to writing the
first draft of the chapter on Dictionaries, he provided continual guidance in the early
stages of the book.
• Christoph Zwerschke sent several corrections and pedagogic suggestions, and explained
the difference between gleich and selbe.
xvi | Preface
www.it-ebooks.info
• James Mayer sent us a whole slew of spelling and typographical errors, including two in
the contributor list.
• Hayden McAfee caught a potentially confusing inconsistency between two examples.
• Angel Arnal is part of an international team of translators working on the Spanish version
of the text. He has also found several errors in the English version.
• Tauhidul Hoque and Lex Berezhny created the illustrations in Chapter 1 and improved
many of the other illustrations.
• Dr. Michele Alzetta caught an error in Chapter 8 and sent some interesting pedagogic
comments and suggestions about Fibonacci and Old Maid.
• Andy Mitchell caught a typo in Chapter 1 and a broken example in Chapter 2.
• Kalin Harvey suggested a clarification in Chapter 7 and caught some typos.
• Christopher P. Smith caught several typos and helped us update the book for Python 2.2.
• David Hutchins caught a typo in the Foreword.
• Gregor Lingl is teaching Python at a high school in Vienna, Austria. He is working on a
German translation of the book, and he caught a couple of bad errors in Chapter 5.
• Julie Peters caught a typo in the Preface.
• Florin Oprina sent in an improvement in makeTime, a correction in printTime, and a nice
typo.
• D. J. Webre suggested a clarification in Chapter 3.
• Ken found a fistful of errors in Chapters 8, 9 and 11.
• Ivo Wever caught a typo in Chapter 5 and suggested a clarification in Chapter 3.
• Curtis Yanko suggested a clarification in Chapter 2.
• Ben Logan sent in a number of typos and problems with translating the book into HTML.
• Jason Armstrong saw the missing word in Chapter 2.
• Louis Cordier noticed a spot in Chapter 16 where the code didn’t match the text.
• Brian Cain suggested several clarifications in Chapters 2 and 3.
• Rob Black sent in a passel of corrections, including some changes for Python 2.2.
• Jean-Philippe Rey at Ecole Centrale Paris sent a number of patches, including some
updates for Python 2.2 and other thoughtful improvements.
• Jason Mader at George Washington University made a number of useful suggestions and
corrections.
• Jan Gundtofte-Bruun reminded us that “a error” is an error.
• Abel David and Alexis Dinno reminded us that the plural of “matrix” is “matrices”, not
“matrixes”. This error was in the book for years, but two readers with the same initials
reported it on the same day. Weird.
• Charles Thayer encouraged us to get rid of the semicolons we had put at the ends of some
statements and to clean up our use of “argument” and “parameter”.
• Roger Sperberg pointed out a twisted piece of logic in Chapter 3.
• Sam Bull pointed out a confusing paragraph in Chapter 2.
Preface | xvii
www.it-ebooks.info
• Andrew Cheung pointed out two instances of “use before def ”.
• C. Corey Capel spotted a missing word and a typo in Chapter 4.
• Alessandra helped clear up some Turtle confusion.
• Wim Champagne found a braino in a dictionary example.
• Douglas Wright pointed out a problem with floor division in arc.
• Jared Spindor found some jetsam at the end of a sentence.
• Lin Peiheng sent a number of very helpful suggestions.
• Ray Hagtvedt sent in two errors and a not-quite-error.
• Torsten Hübsch pointed out an inconsistency in Swampy.
• Inga Petuhhov corrected an example in Chapter 14.
• Arne Babenhauserheide sent several helpful corrections.
• Mark E. Casida is is good at spotting repeated words.
• Scott Tyler filled in a that was missing. And then sent in a heap of corrections.
• Gordon Shephard sent in several corrections, all in separate emails.
• Andrew Turner spotted an error in 
[END CHUNK 2/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 2/7]

## USER
[START CHUNK 3/7]
Chapter 8.
• Adam Hobart fixed a problem with floor division in arc.
• Daryl Hammond and Sarah Zimmerman pointed out that I served up math.pi too early.
And Zim spotted a typo.
• George Sass found a bug in a Debugging section.
• Brian Bingham suggested Exercise 11-5.
• Leah Engelbert-Fenton pointed out that I used tuple as a variable name, contrary to my
own advice. And then found a bunch of typos and a “use before def ”.
• Joe Funke spotted a typo.
• Chao-chao Chen found an inconsistency in the Fibonacci example.
• Jeff Paine knows the difference between space and spam.
• Lubos Pintes sent in a typo.
• Gregg Lind and Abigail Heithoff suggested Exercise 14-3.
• Max Hailperin has sent in a number of corrections and suggestions. Max is one of the
authors of the extraordinary Concrete Abstractions (Course Technology, 1998), which you
might want to read when you are done with this book.
• Chotipat Pornavalai found an error in an error message.
• Stanislaw Antol sent a list of very helpful suggestions.
• Eric Pashman sent a number of corrections for Chapters 4–11.
• Miguel Azevedo found some typos.
• Jianhua Liu sent in a long list of corrections.
• Nick King found a missing word.
• Martin Zuther sent a long list of suggestions.
xviii | Preface
www.it-ebooks.info
• Adam Zimmerman found an inconsistency in my instance of an “instance” and several
other errors.
• Ratnakar Tiwari suggested a footnote explaining degenerate triangles.
• Anurag Goel suggested another solution for is_abecedarian and sent some additional
corrections. And he knows how to spell Jane Austen.
• Kelli Kratzer spotted one of the typos.
• Mark Griffiths pointed out a confusing example in Chapter 3.
• Roydan Ongie found an error in my Newton’s method.
• Patryk Wolowiec helped me with a problem in the HTML version.
• Mark Chonofsky told me about a new keyword in Python 3.
• Russell Coleman helped me with my geometry.
• Wei Huang spotted several typographical errors.
• Karen Barber spotted the the oldest typo in the book.
• Nam Nguyen found a typo and pointed out that I used the Decorator pattern but didn’t
mention it by name.
• Stéphane Morin sent in several corrections and suggestions.
• Paul Stoop corrected a typo in uses_only.
• Eric Bronner pointed out a confusion in the discussion of the order of operations.
• Alexandros Gezerlis set a new standard for the number and quality of suggestions he sub‐
mitted. We are deeply grateful!
• Gray Thomas knows his right from his left.
• Giovanni Escobar Sosa sent a long list of corrections and suggestions.
• Alix Etienne fixed one of the URLs.
• Kuang He found a typo.
• Daniel Neilson corrected an error about the order of operations.
• Will McGinnis pointed out that polyline was defined differently in two places.
• Swarup Sahoo spotted a missing semicolon.
• Frank Hecker pointed out an exercise that was under-specified, and some broken links.
• Animesh B helped me clean up a confusing example.
• Martin Caspersen found two round-off errors.
• Gregor Ulm sent several corrections and suggestions.
• Dimitrios Tsirigkas suggested I clarify an exercise.
• Carlos Tafur sent a page of corrections and suggestions.
• Martin Nordsletten found a bug in an exercise solution.
• Lars O.D. Christensen found a broken reference.
• Victor Simeone found a typo.
• Sven Hoexter pointed out that a variable named input shadows a build-in function.
• Viet Le found a typo.
Preface | xix
www.it-ebooks.info
• Stephen Gregory pointed out the problem with cmp in Python 3.
• Matthew Shultz let me know about a broken link.
• Lokesh Kumar Makani let me know about some broken links and some changes in error
messages.
• Ishwar Bhat corrected my statement of Fermat’s last theorem.
• Brian McGhie suggested a clarification.
• Andrea Zanella translated the book into Italian, and sent a number of corrections along
the way.
• Many, many thanks to Melissa Lewis and Luciano Ramalho for excellent comments and
suggestions on the second edition.
• Thanks to Harry Percival from PythonAnywhere for his help getting people started run‐
ning Python in a browser.
• Xavier Van Aubel made several useful corrections in the second edition.
xx | Preface
www.it-ebooks.info
CHAPTER 1
The Way of the Program
The goal of this book is to teach you to think like a computer scientist. This way of
thinking combines some of the best features of mathematics, engineering, and natural
science. Like mathematicians, computer scientists use formal languages to denote
ideas (specifically computations). Like engineers, they design things, assembling
components into systems and evaluating tradeoffs among alternatives. Like scientists,
they observe the behavior of complex systems, form hypotheses, and test predictions.
The single most important skill for a computer scientist is problem solving. Problem
solving means the ability to formulate problems, think creatively about solutions, and
express a solution clearly and accurately. As it turns out, the process of learning to
program is an excellent opportunity to practice problem-solving skills. That’s why
this chapter is called “The Way of the Program”.
On one level, you will be learning to program, a useful skill by itself. On another level,
you will use programming as a means to an end. As we go along, that end will
become clearer.
What Is a Program?
A program is a sequence of instructions that specifies how to perform a computation.
The computation might be something mathematical, such as solving a system of
equations or finding the roots of a polynomial, but it can also be a symbolic computa‐
tion, such as searching and replacing text in a document or something graphical, like
processing an image or playing a video.
The details look different in different languages, but a few basic instructions appear in
just about every language:
1
www.it-ebooks.info
input:
Get data from the keyboard, a file, the network, or some other device.
output:
Display data on the screen, save it in a file, send it over the network, etc.
math:
Perform basic mathematical operations like addition and multiplication.
conditional execution:
Check for certain conditions and run the appropriate code.
repetition:
Perform some action repeatedly, usually with some variation.
Believe it or not, that’s pretty much all there is to it. Every program you’ve ever used,
no matter how complicated, is made up of instructions that look pretty much like
these. So you can think of programming as the process of breaking a large, complex
task into smaller and smaller subtasks until the subtasks are simple enough to be per‐
formed with one of these basic instructions.
Running Python
One of the challenges of getting started with Python is that you might have to install
Python and related software on your computer. If you are familiar with your operat‐
ing system, and especially if you are comfortable with the command-line interface,
you will have no trouble installing Python. But for beginners, it can be painful to
learn about system administration and programming at the same time.
To avoid that problem, I recommend that you start out running Python in a browser.
Later, when you are comfortable with Python, I’ll make suggestions for installing
Python on your computer.
There are a number of web pages you can use to run Python. If you already have a
favorite, go ahead and use it. Otherwise I recommend PythonAnywhere. I provide
detailed instructions for getting started at http://tinyurl.com/thinkpython2e.
There are two versions of Python, called Python 2 and Python 3. They are very simi‐
lar, so if you learn one, it is easy to switch to the other. In fact, there are only a few
differences you will encounter as a beginner. This book is written for Python 3, but I
include some notes about Python 2.
The Python interpreter is a program that reads and executes Python code. Depend‐
ing on your environment, you might start the interpreter by clicking on an icon, or by
typing python on a command line. When it starts, you 
[END CHUNK 3/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 3/7]

## USER
[START CHUNK 4/7]
should see output like this:
2 | Chapter 1: The Way of the Program
www.it-ebooks.info
Python 3.4.0 (default, Jun 19 2015, 14:20:21)
[GCC 4.8.2] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
The first three lines contain information about the interpreter and the operating sys‐
tem it’s running on, so it might be different for you. But you should check that the
version number, which is 3.4.0 in this example, begins with 3, which indicates that
you are running Python 3. If it begins with 2, you are running (you guessed it)
Python 2.
The last line is a prompt that indicates that the interpreter is ready for you to enter
code. If you type a line of code and hit Enter, the interpreter displays the result:
>>> 1 + 1
2
Now you’re ready to get started. From here on, I assume that you know how to start
the Python interpreter and run code.
The First Program
Traditionally, the first program you write in a new language is called “Hello, World!”
because all it does is display the words “Hello, World!” In Python, it looks like this:
>>> print('Hello, World!')
This is an example of a print statement, although it doesn’t actually print anything on
paper. It displays a result on the screen. In this case, the result is the words
Hello, World!
The quotation marks in the program mark the beginning and end of the text to be
displayed; they don’t appear in the result.
The parentheses indicate that print is a function. We’ll get to functions in Chapter 3.
In Python 2, the print statement is slightly different; it is not a function, so it doesn’t
use parentheses.
>>> print 'Hello, World!'
This distinction will make more sense soon, but that’s enough to get started.
Arithmetic Operators
After “Hello, World”, the next step is arithmetic. Python provides operators, which
are special symbols that represent computations like addition and multiplication.
The operators +, -, and * perform addition, subtraction, and multiplication, as in the
following examples:
The First Program | 3
www.it-ebooks.info
>>> 40 + 2
42
>>> 43 - 1
42
>>> 6 * 7
42
The operator / performs division:
>>> 84 / 2
42.0
You might wonder why the result is 42.0 instead of 42. I’ll explain in the next section.
Finally, the operator ** performs exponentiation; that is, it raises a number to a
power:
>>> 6**2 + 6
42
In some other languages, ^ is used for exponentiation, but in Python it is a bitwise
operator called XOR. If you are not familiar with bitwise operators, the result will
surprise you:
>>> 6 ^ 2
4
I won’t cover bitwise operators in this book, but you can read about them at http://
wiki.python.org/moin/BitwiseOperators.
Values and Types
A value is one of the basic things a program works with, like a letter or a number.
Some values we have seen so far are 2, 42.0, and 'Hello, World!'
These values belong to different types: 2 is an integer, 42.0 is a oating-point num‐
ber, and 'Hello, World!' is a string, so-called because the letters it contains are
strung together.
If you are not sure what type a value has, the interpreter can tell you:
>>> type(2)
<class 'int'>
>>> type(42.0)
<class 'float'>
>>> type('Hello, World!')
<class 'str'>
In these results, the word “class” is used in the sense of a category; a type is a category
of values.
4 | Chapter 1: The Way of the Program
www.it-ebooks.info
Not surprisingly, integers belong to the type int, strings belong to str, and floatingpoint numbers belong to float.
What about values like '2' and '42.0'? They look like numbers, but they are in quo‐
tation marks like strings:
>>> type('2')
<class 'str'>
>>> type('42.0')
<class 'str'>
They’re strings.
When you type a large integer, you might be tempted to use commas between groups
of digits, as in 1,000,000. This is not a legal integer in Python, but it is legal:
>>> 1,000,000
(1, 0, 0)
That’s not what we expected at all! Python interprets 1,000,000 as a commaseparated sequence of integers. We’ll learn more about this kind of sequence later.
Formal and Natural Languages
Natural languages are the languages people speak, such as English, Spanish, and
French. They were not designed by people (although people try to impose some order
on them); they evolved naturally.
Formal languages are languages that are designed by people for specific applications.
For example, the notation that mathematicians use is a formal language that is partic‐
ularly good at denoting relationships among numbers and symbols. Chemists use a
formal language to represent the chemical structure of molecules. And most impor‐
tantly:
Programming languages are formal languages that have been designed to express
computations.
Formal languages tend to have strict syntax rules that govern the structure of state‐
ments. For example, in mathematics the statement 3 + 3 = 6 has correct syntax, but
3 + = 3$6 does not. In chemistry H2O is a syntactically correct formula, but 2Zz is
not.
Syntax rules come in two flavors, pertaining to tokens and structure. Tokens are the
basic elements of the language, such as words, numbers, and chemical elements. One
of the problems with 3 + = 3$6 is that $ is not a legal token in mathematics (at least
as far as I know). Similarly, 2Zz is not legal because there is no element with the
abbreviation Zz.
Formal and Natural Languages | 5
www.it-ebooks.info
The second type of syntax rule pertains to the way tokens are combined. The equa‐
tion 3 + = 3 is illegal because even though + and = are legal tokens, you can’t have
one right after the other. Similarly, in a chemical formula the subscript comes after
the element name, not before.
This is @ well-structured Engli$h sentence with invalid t*kens in it. This sentence all
valid tokens has, but invalid structure with.
When you read a sentence in English or a statement in a formal language, you have to
figure out the structure (although in a natural language you do this subconsciously).
This process is called parsing.
Although formal and natural languages have many features in common—tokens,
structure, and syntax—there are some differences:
ambiguity:
Natural languages are full of ambiguity, which people deal with by using contex‐
tual clues and other information. Formal languages are designed to be nearly or
completely unambiguous, which means that any statement has exactly one mean‐
ing, regardless of context.
redundancy:
In order to make up for ambiguity and reduce misunderstandings, natural lan‐
guages employ lots of redundancy. As a result, they are often verbose. Formal
languages are less redundant and more concise.
literalness:
Natural languages are full of idiom and metaphor. If I say, “The penny dropped”,
there is probably no penny and nothing dropping (this idiom means that some‐
one understood something after a period of confusion). Formal languages mean
exactly what they say.
Because we all grow up speaking natural languages, it is sometimes hard to adjust to
formal languages. The difference between formal and natural language is like the dif‐
ference between poetry and prose, but more so:
Poetry:
Words are used for their sounds as well as for their meaning, and the whole
poem together creates an effect or emotional response. Ambiguity is not only
common but often deliberate.
Prose:
The literal meaning of words is more important, and the structure contributes
more meaning. Prose is more amenable to analysis than poetry but still often
ambiguous.
6 | Chapter 1: The Way of the Program
www.it-ebooks.info
Programs:
The meaning of a computer program is unambiguous and literal, and can be
understood entirely by analysis of the tokens and structure.
Formal languages are more dense than natural languages, so it takes longer to read
them. Also, the structure is important, so it is not always best to read from top to bot‐
tom, left to right. Instead, learn to parse the program in your head, identifying the
tokens and interpreting the structure. Finally, the details matter. Small errors in spell‐
ing and punctuation, which you can get away with in 
[END CHUNK 4/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 4/7]

## USER
[START CHUNK 5/7]
natural languages, can make a
big difference in a formal language.
Debugging
Programmers make mistakes. For whimsical reasons, programming errors are called
bugs and the process of tracking them down is called debugging.
Programming, and especially debugging, sometimes brings out strong emotions. If
you are struggling with a difficult bug, you might feel angry, despondent, or embar‐
rassed.
There is evidence that people naturally respond to computers as if they were people.
When they work well, we think of them as teammates, and when they are obstinate or
rude, we respond to them the same way we respond to rude, obstinate people (Reeves
and Nass, e Media Equation: How People Treat Computers, Television, and New
Media Like Real People and Places).
Preparing for these reactions might help you deal with them. One approach is to
think of the computer as an employee with certain strengths, like speed and preci‐
sion, and particular weaknesses, like lack of empathy and inability to grasp the big
picture.
Your job is to be a good manager: find ways to take advantage of the strengths and
mitigate the weaknesses. And find ways to use your emotions to engage with the
problem, without letting your reactions interfere with your ability to work effectively.
Learning to debug can be frustrating, but it is a valuable skill that is useful for many
activities beyond programming. At the end of each chapter there is a section, like this
one, with my suggestions for debugging. I hope they help!
Debugging | 7
www.it-ebooks.info
Glossary
problem solving:
The process of formulating a problem, finding a solution, and expressing it.
high-level language:
A programming language like Python that is designed to be easy for humans to
read and write.
low-level language:
A programming language that is designed to be easy for a computer to run; also
called “machine language” or “assembly language”.
portability:
A property of a program that can run on more than one kind of computer.
interpreter:
A program that reads another program and executes it.
prompt:
Characters displayed by the interpreter to indicate that it is ready to take input
from the user.
program:
A set of instructions that specifies a computation.
print statement:
An instruction that causes the Python interpreter to display a value on the screen.
operator:
A special symbol that represents a simple computation like addition, multiplica‐
tion, or string concatenation.
value:
One of the basic units of data, like a number or string, that a program
manipulates.
type:
A category of values. The types we have seen so far are integers (type int),
floating-point numbers (type float), and strings (type str).
integer:
A type that represents whole numbers.
oating-point:
A type that represents numbers with fractional parts.
8 | Chapter 1: The Way of the Program
www.it-ebooks.info
string:
A type that represents sequences of characters.
natural language:
Any one of the languages that people speak that evolved naturally.
formal language:
Any one of the languages that people have designed for specific purposes, such as
representing mathematical ideas or computer programs; all programming lan‐
guages are formal languages.
token:
One of the basic elements of the syntactic structure of a program, analogous to a
word in a natural language.
syntax:
The rules that govern the structure of a program.
parse:
To examine a program and analyze the syntactic structure.
bug:
An error in a program.
debugging:
The process of finding and correcting bugs.
Exercises
Exercise 1-1.
It is a good idea to read this book in front of a computer so you can try out the exam‐
ples as you go.
Whenever you are experimenting with a new feature, you should try to make mis‐
takes. For example, in the “Hello, world!” program, what happens if you leave out one
of the quotation marks? What if you leave out both? What if you spell print wrong?
This kind of experiment helps you remember what you read; it also helps when you
are programming, because you get to know what the error messages mean. It is better
to make mistakes now and on purpose than later and accidentally.
1. In a print statement, what happens if you leave out one of the parentheses, or
both?
2. If you are trying to print a string, what happens if you leave out one of the quota‐
tion marks, or both?
Exercises | 9
www.it-ebooks.info
3. You can use a minus sign to make a negative number like -2. What happens if
you put a plus sign before a number? What about 2++2?
4. In math notation, leading zeros are okay, as in 02. What happens if you try this in
Python?
5. What happens if you have two values with no operator between them?
Exercise 1-2.
Start the Python interpreter and use it as a calculator.
1. How many seconds are there in 42 minutes 42 seconds?
2. How many miles are there in 10 kilometers? Hint: there are 1.61 kilometers in a
mile.
3. If you run a 10 kilometer race in 42 minutes 42 seconds, what is your average
pace (time per mile in minutes and seconds)? What is your average speed in
miles per hour?
10 | Chapter 1: The Way of the Program
www.it-ebooks.info
CHAPTER 2
Variables, Expressions and Statements
One of the most powerful features of a programming language is the ability to
manipulate variables. A variable is a name that refers to a value.
Assignment Statements
An assignment statement creates a new variable and gives it a value:
>>> message = 'And now for something completely different'
>>> n = 17
>>> pi = 3.141592653589793
This example makes three assignments. The first assigns a string to a new variable
named message; the second gives the integer 17 to n; the third assigns the (approxi‐
mate) value of π to pi.
A common way to represent variables on paper is to write the name with an arrow
pointing to its value. This kind of figure is called a state diagram because it shows
what state each of the variables is in (think of it as the variable’s state of mind).
Figure 2-1 shows the result of the previous example.
Figure 2-1. State diagram.
11
www.it-ebooks.info
Variable Names
Programmers generally choose names for their variables that are meaningful—they
document what the variable is used for.
Variable names can be as long as you like. They can contain both letters and numbers,
but they can’t begin with a number. It is legal to use uppercase letters, but it is conven‐
tional to use only lowercase for variables names.
The underscore character, _, can appear in a name. It is often used in names with
multiple words, such as your_name or airspeed_of_unladen_swallow.
If you give a variable an illegal name, you get a syntax error:
>>> 76trombones = 'big parade'
SyntaxError: invalid syntax
>>> more@ = 1000000
SyntaxError: invalid syntax
>>> class = 'Advanced Theoretical Zymurgy'
SyntaxError: invalid syntax
76trombones is illegal because it begins with a number. more@ is illegal because it con‐
tains an illegal character, @. But what’s wrong with class?
It turns out that class is one of Python’s keywords. The interpreter uses keywords to
recognize the structure of the program, and they cannot be used as variable names.
Python 3 has these keywords:
False class finally is return
None continue for lambda try
True def from nonlocal while
and del global not with
as elif if or yield
assert else import pass
break except in raise
You don’t have to memorize this list. In most development environments, keywords
are displayed in a different color; if you try to use one as a variable name, you’ll know.
Expressions and Statements
An expression is a combination of values, variables, and operators. A value all by
itself is considered an expression, and so is a variable, so the following are all legal
expressions:
12 | Chapter 2: Variables, Expressions and Statements
www.it-ebooks.info
>>> 42
42
>>> n
17
>>> n + 25
42
When you type an expression at the prompt, the interpreter evaluates it, which
means that it finds the value of the expression. In this example, n has the value 17 and
n + 25 has the value 42.
A statement is 
[END CHUNK 5/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 5/7]

## USER
[START CHUNK 6/7]
a unit of code that has an effect, like creating a variable or displaying a
value.
>>> n = 17
>>> print(n)
The first line is an assignment statement that gives a value to n. The second line is a
print statement that displays the value of n.
When you type a statement, the interpreter executes it, which means that it does
whatever the statement says. In general, statements don’t have values.
Script Mode
So far we have run Python in interactive mode, which means that you interact
directly with the interpreter. Interactive mode is a good way to get started, but if you
are working with more than a few lines of code, it can be clumsy.
The alternative is to save code in a file called a script and then run the interpreter in
script mode to execute the script. By convention, Python scripts have names that end
with .py.
If you know how to create and run a script on your computer, you are ready to go.
Otherwise I recommend using PythonAnywhere again. I have posted instructions for
running in script mode at http://tinyurl.com/thinkpython2e.
Because Python provides both modes, you can test bits of code in interactive mode
before you put them in a script. But there are differences between interactive mode
and script mode that can be confusing.
For example, if you are using Python as a calculator, you might type:
>>> miles = 26.2
>>> miles * 1.61
42.182
The first line assigns a value to miles, but it has no visible effect. The second line is
an expression, so the interpreter evaluates it and displays the result. It turns out that a
marathon is about 42 kilometers.
Script Mode | 13
www.it-ebooks.info
But if you type the same code into a script and run it, you get no output at all. In
script mode an expression, all by itself, has no visible effect. Python actually evaluates
the expression, but it doesn’t display the value unless you tell it to:
miles = 26.2
print(miles * 1.61)
This behavior can be confusing at first.
A script usually contains a sequence of statements. If there is more than one state‐
ment, the results appear one at a time as the statements execute.
For example, the script
print(1)
x = 2
print(x)
produces the output
1
2
The assignment statement produces no output.
To check your understanding, type the following statements in the Python interpreter
and see what they do:
5
x = 5
x + 1
Now put the same statements in a script and run it. What is the output? Modify the
script by transforming each expression into a print statement and then run it again.
Order of Operations
When an expression contains more than one operator, the order of evaluation
depends on the order of operations. For mathematical operators, Python follows
mathematical convention. The acronym PEMDAS is a useful way to remember the
rules:
• Parentheses have the highest precedence and can be used to force an expression
to evaluate in the order you want. Since expressions in parentheses are evaluated
first, 2 * (3-1) is 4, and (1+1)**(5-2) is 8. You can also use parentheses to
make an expression easier to read, as in (minute * 100) / 60, even if it doesn’t
change the result.
• Exponentiation has the next highest precedence, so 1 + 2**3 is 9, not 27, and 2
* 3**2 is 18, not 36.
14 | Chapter 2: Variables, Expressions and Statements
www.it-ebooks.info
• Multiplication and Division have higher precedence than Addition and Subtrac‐
tion. So 2*3-1 is 5, not 4, and 6+4/2 is 8, not 5.
• Operators with the same precedence are evaluated from left to right (except
exponentiation). So in the expression degrees / 2 * pi, the division happens
first and the result is multiplied by pi. To divide by 2π, you can use parentheses
or write degrees / 2 / pi.
I don’t work very hard to remember the precedence of operators. If I can’t tell by
looking at the expression, I use parentheses to make it obvious.
String Operations
In general, you can’t perform mathematical operations on strings, even if the strings
look like numbers, so the following are illegal:
'2'-'1' 'eggs'/'easy' 'third'*'a charm'
But there are two exceptions, + and *.
The + operator performs string concatenation, which means it joins the strings by
linking them end-to-end. For example:
>>> first = 'throat'
>>> second = 'warbler'
>>> first + second
throatwarbler
The * operator also works on strings; it performs repetition. For example, 'Spam'*3 is
'SpamSpamSpam'. If one of the values is a string, the other has to be an integer.
This use of + and * makes sense by analogy with addition and multiplication. Just as
4*3 is equivalent to 4+4+4, we expect 'Spam'*3 to be the same as
'Spam'+'Spam'+'Spam', and it is. On the other hand, there is a significant way in
which string concatenation and repetition are different from integer addition and
multiplication. Can you think of a property that addition has that string concatena‐
tion does not?
Comments
As programs get bigger and more complicated, they get more difficult to read. Formal
languages are dense, and it is often difficult to look at a piece of code and figure out
what it is doing, or why.
For this reason, it is a good idea to add notes to your programs to explain in natural
language what the program is doing. These notes are called comments, and they start
with the # symbol:
String Operations | 15
www.it-ebooks.info
# compute the percentage of the hour that has elapsed
percentage = (minute * 100) / 60
In this case, the comment appears on a line by itself. You can also put comments at
the end of a line:
percentage = (minute * 100) / 60 # percentage of an hour
Everything from the # to the end of the line is ignored—it has no effect on the execu‐
tion of the program.
Comments are most useful when they document non-obvious features of the code. It
is reasonable to assume that the reader can figure out what the code does; it is more
useful to explain why.
This comment is redundant with the code and useless:
v = 5 # assign 5 to v
This comment contains useful information that is not in the code:
v = 5 # velocity in meters/second.
Good variable names can reduce the need for comments, but long names can make
complex expressions hard to read, so there is a trade-off.
Debugging
Three kinds of errors can occur in a program: syntax errors, runtime errors, and
semantic errors. It is useful to distinguish between them in order to track them down
more quickly.
Syntax error:
“Syntax” refers to the structure of a program and the rules about that structure.
For example, parentheses have to come in matching pairs, so (1 + 2) is legal, but
8) is a syntax error.
If there is a syntax error anywhere in your program, Python displays an error
message and quits, and you will not be able to run the program. During the first
few weeks of your programming career, you might spend a lot of time tracking
down syntax errors. As you gain experience, you will make fewer errors and find
them faster.
Runtime error:
The second type of error is a runtime error, so called because the error does not
appear until after the program has started running. These errors are also called
exceptions because they usually indicate that something exceptional (and bad)
has happened.
16 | Chapter 2: Variables, Expressions and Statements
www.it-ebooks.info
Runtime errors are rare in the simple programs you will see in the first few chap‐
ters, so it might be a while before you encounter one.
Semantic error:
The third type of error is “semantic”, which means related to meaning. If there is
a semantic error in your program, it will run without generating error messages,
but it will not do the right thing. It will do something else. Specifically, it will do
what you told it to do.
Identifying semantic errors can be tricky because it requires you to work back‐
ward by looking at the output of the program and trying to figure out what it is
doing.
Glossary
variable:
A name that refers to a value.
assignment:
A statement that assigns a value to a variable.
state diagram:
A graphical representation of a set of variables and the values they refer to.
keyword:
A 
[END CHUNK 6/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 6/7]

## USER
[START CHUNK 7/7]
reserved word that is used to parse a program; you cannot use keywords like
if, def, and while as variable names.
operand:
One of the values on which an operator operates.
expression:
A combination of variables, operators, and values that represents a single result.
evaluate:
To simplify an expression by performing the operations in order to yield a single
value.
statement:
A section of code that represents a command or action. So far, the statements we
have seen are assignments and print statements.
execute:
To run a statement and do what it says.
interactive mode:
A way of using the Python interpreter by typing code at the prompt.
Glossary | 17
www.it-ebooks.info
script mode:
A way of using the Python interpreter to read code from a script and run it.
script:
A program stored in a file.
order of operations:
Rules governing the order in which expressions involving multiple operators and
operands are evaluated.
concatenate:
To join two operands end-to-end.
comment:
Information in a program that is meant for other programmers (or anyone read‐
ing the source code) and has no effect on the execution of the program.
syntax error:
An error in a program that makes it impossible to parse (and therefore impossi‐
ble to interpret).
exception:
An error that is detected while the program is running.
semantics:
The meaning of a program.
semantic error:
An error in a program that makes it do something other than what the program‐
mer intended.
Exercises
Exercise 2-1.
Repeating my advice from the previous chapter, whenever you learn a new feature,
you should try it out in interactive mode and make errors on purpose to see what
goes wrong.
• We’ve seen that n = 42 is legal. What about 42 = n?
• How about x = y = 1?
• In some languages every statement ends with a semicolon, ;. What happens if
you put a semicolon at the end of a Python statement?
18 | Chapter 2: Variables, Expressions and Statements
www.it-ebooks.info
• What if you put a period at the end of a statement?
• In math notation you can multiply x and y like this: xy. What happens if you try
that in Python?
Exercise 2-2.
Practice using the Python interpreter as a calculator:
1. The volume of a sphere with radius r is 43πr3. What is the volume of a sphere with
radius 5?
2. Suppose the cover price of a book is $24.95, but bookstores get a 40% discount.
Shipping costs $3 for the first copy and 75 cents for each additional copy. What is
the total wholesale cost for 60 copies?
3. If I leave my house at 6:52 am and run 1 mile at an easy pace (8:15 per mile), then
3 miles at tempo (7:12 per mile) and 1 mile at an easy pace again, what time do I
get home for breakfast?
Exercises | 19
www.it-ebooks.info
www.it-ebooks.info
CHAPTER 3
Functions
In the context of programming, a function is a named sequence of statements that
performs a computation. When you define a function, you specify the name and the
sequence of statements. Later, you can “call” the function by name.
Function Calls
We have already seen one example of a function call:
>>> type(42)
<class 'int'>
The name of the function is type. The expression in parentheses is called the argu‐
ment of the function. The result, for this function, is the type of the argument.
It is common to say that a function “takes” an argument and “returns” a result. The
result is also called the return value.
Python provides functions that convert values from one type to another. The int
function takes any value and converts it to an integer, if it can, or complains other‐
wise:
>>> int('32')
32
>>> int('Hello')
ValueError: invalid literal for int(): Hello
int can convert floating-point values to integers, but it doesn’t round off; it chops off
the fraction part:
>>> int(3.99999)
3
>>> int(-2.3)
-2
21
www.it-ebooks.info
float converts integers and strings to floating-point numbers:
>>> float(32)
32.0
>>> float('3.14159')
3.14159
Finally, str converts its argument to a string:
>>> str(32)
'32'
>>> str(3.14159)
'3.14159'
Math Functions
Python has a math module that provides most of the familiar mathematical functions.
A module is a file that contains a collection of related functions.
Before we can use the functions in a module, we have to import it with an import
statement:
>>> import math
This statement creates a module object named math. If you display the module
object, you get some information about it:
>>> math
<module 'math' (built-in)>
The module object contains the functions and variables defined in the module. To
access one of the functions, you have to specify the name of the module and the name
of the function, separated by a dot (also known as a period). This format is called dot
notation.
>>> ratio = signal_power / noise_power
>>> decibels = 10 * math.log10(ratio)
>>> radians = 0.7
>>> height = math.sin(radians)
The first example uses math.log10 to compute a signal-to-noise ratio in decibels
(assuming that signal_power and noise_power are defined). The math module also
provides log, which computes logarithms base e.
The second example finds the sine of radians. The name of the variable is a hint that
sin and the other trigonometric functions (cos, tan, etc.) take arguments in radians.
To convert from degrees to radians, divide by 180 and multiply by π:
22 | Chapter 3: Functions
www.it-ebooks.info
>>> degrees = 45
>>> radians = degrees / 180.0 * math.pi
>>> math.sin(radians)
0.707106781187
The expression math.pi gets the variable pi from the math module. Its value is a
floating-point approximation of π, accurate to about 15 digits.
If you know trigonometry, you can check the previous result by comparing it to the
square root of 2 divided by 2:
>>> math.sqrt(2) / 2.0
0.707106781187
Composition
So far, we have looked at the elements of a program—variables, expressions, and
statements—in isolation, without talking about how to combine them.
One of the most useful features of programming languages is their ability to take
small building blocks and compose them. For example, the argument of a function
can be any kind of expression, including arithmetic operators:
x = math.sin(degrees / 360.0 * 2 * math.pi)
And even function calls:
x = math.exp(math.log(x+1))
Almost anywhere you can put a value, you can put an arbitrary expression, with one
exception: the left side of an assignment statement has to be a variable name. Any
other expression on the left side is a syntax error (we will see exceptions to this rule
later).
>>> minutes = hours * 60 # right
>>> hours * 60 = minutes # wrong!
SyntaxError: can't assign to operator
Adding New Functions
So far, we have only been using the functions that come with Python, but it is also
possible to add new functions. A function definition specifies the name of a new
function and the sequence of statements that run when the function is called.
Here is an example:
def print_lyrics():
 print("I'm a lumberjack, and I'm okay.")
 print("I sleep all night and I work all day.")
Composition | 23
www.it-ebooks.info
def is a keyword that indicates that this is a function definition. The name of the
function is print_lyrics. The rules for function names are the same as for variable
names: letters, numbers and underscore are legal, but the first character can’t be a
number. You can’t use a keyword as the name of a function, and you should avoid
having a variable and a function with the same name.
The empty parentheses after the name indicate that this function doesn’t take any
arguments.
The first line of the function definition is called the header; the rest is called the
body. The header has to end with a colon and the body has to be indented. By con‐
vention, indentation is always four spaces. The body can contain any number of state‐
ments.
The strings in the print statements are enclosed in double quotes. Single quotes and
double quotes do the same thing; most people use single quot
[END CHUNK 7/7]
Reply with OK: [CHUNK x/TOTAL]
Don't reply with anything else!

## ASSISTANT
OK: [CHUNK 7/7]

## USER
provide a digestible and academic summary of what you just read

## ASSISTANT
The text appears to be an introductory guide to programming in Python, covering fundamental concepts and practices. It is divided into several chapters, each focusing on specific topics. Here's a breakdown:

### Chapter 1: The Way of the Program
- Introduces the basic elements of programming, such as problem-solving, high-level and low-level languages, and debugging.
- Discusses the difference between natural languages and formal languages, emphasizing the importance of syntax and semantics.

### Chapter 2: Variables, Expressions, and Statements
- Explains variables, assignment statements, and the types of data (integers, floating-point numbers, and strings).
- Covers the order of operations and introduces the concept of expressions and statements.
- Discusses the importance of comments for code readability and introduces three types of errors: syntax errors, runtime errors, and semantic errors.

### Chapter 3: Functions
- Introduces the concept of functions, both built-in and user-defined.
- Discusses the math module in Python and how to use its functions.
- Explains function composition, where the output of one function becomes the input of another.
- Describes how to define a new function using the `def` keyword.

Throughout the text, the author emphasizes the importance of debugging as an integral part of the programming process. The guide also includes exercises at the end of each chapter to reinforce the concepts discussed.

Overall, the text serves as a comprehensive beginner's guide to Python programming, focusing on foundational concepts and best practices.