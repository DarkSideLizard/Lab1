# Lab1
1.15 Main Lab#1: Do As I'm Doing

The Nature of Main Lab Assignments

We refer to our programming assignments as "Labs" because we expect that you will have to do some experimentation to complete them. You should not expect your programs to work the first time you run them. Please be inquisitive, curious and humble; the labs are intended as context for you to discover, learn and practice.

You will soon discover by first hand experience that it is hard to write a program that flawlessly responds as your users might expect it to. The same is true of zyBooks and the other programs you will use in this class. However, if your program does not generate the results you are expecting, do not rush to the conclusion that C++ is broken. Billions of lines of code have been written in C++, it is extremely unlikely that you have found an error in C++. Take the time to look at your output and try to understand what C++ is doing with your code. Then make adjustments so that your program produces the output that is required. (FYI, for those interested, zyBooks compiles with C++ 14 as the default).

Reminder

This lab is to be done individually, not with pair programming. For all main labs, before you start coding, 1) read through the entire specification, 2) view the help video for the lab, and 3) think through at a high level how your full solution will look. Then start coding.

Background

As a big fan of BYU you want to write a list of BYU trivia, but as a programmer you want to make it nicely formated.

Requirements

Your goal is to simply exactly replicate the output shown below. Producing this output is worth 75 points.

                                Basic BYU Trivia

                Questions                               Answers

What was the original name of BYU?              Brigham Young Academy
When was BYU established?                       1875
Who was the first "permanent" principal of BYA? Karl G. Maeser
When did BYA become BYU?                        1903
To what sports conference do we belong?         Independent \Football\
When did BYU "win" the national football title? 1984
Who won the Heisman Trophy in 1990?             Ty Detmer
Additional Requirements

Section 1.3 explains that the letters \n, together, cause a new line to be printed. \n is called an “escape sequence” there are other escape sequences such as \t and \". Here is a list of common escape sequences:

\'	Single quote
\"	Double quote
\\	Backslash
\n	New line
\t	Horizontal tab
For this lab you are required to use escape sequences for tabs (\t), backslash(\\) and double quotes (\"). Note that in this context the "horizontal tab" tabs over to the next "tab stop". Tab stops are every 8 characters. Thus a tab will not always move 8 characters, but rather the number needed to get to the next tab stop, which is a multiple of 8 (8, 16, 24, etc.). You will find this to be convenient for lining things up horizontally in this lab.

Items Graded by the TA's Inspection (25 points)

The TA will grade:

Style

Always review the style guide in learning suite for appropriate style. For this lab the only graded style criteria is "Header comments."

Special requirements: Use Escape Sequences where appropriate (Maximum deduction 20 points)

For this lab you must use escape sequences for double quotes, backslash, and horizontal alignment (i.e. tabs). You will lose 5 points (up to the 20 point maximum) each time you fail to use an escape sequence where you should have (i.e. using a bunch of spaces instead of a \t, or some other character to avoid \", etc.).

You may not use "\t \t" since that is a tab, then a space, then a tab; which is not exactly the same as just two tabs: "\t\t", even though the output often looks the same.

Notes

Notes on Escape Sequences

In the early days of C escape sequences were typically used in a long single stream of characters like:

cout << "First \"part\" of text\t\t\tRest of Text\n"; 
These were especially common before the use of the send operator ("<<"). As you might expect the following also works:

cout << "First \"part\" of text" << "\t\t\t" << "Rest of Text" << "\n";
A better way to write this would be:

cout << "First \"part\" of text" << "\t\t\t" << "Rest of Text" << endl;
This style uses "<<" and "endl" to visually separate the formatting from the other text.

Use the more readable style demonstrated in the last example above, and that is what the style guide will require in future labs. For this lab, the only style we are grading is your use of a header. Make sure you follow all the specific requirements given above.

Submission

You will have unlimited submit tries on this lab. Your output must exactly match the output given above. When you code up your solution and hit submit, you will see the differences between what your program outputs, and what we want. After seeing the difference you can correct accordingly. Note that a good way to code is to build and try incrementally. Thus, code up the first line or two and submit. Once that much is right you can move on to the next line or two, etc.

Lateness

If you enroll late in the class, you may have a late date which is 3 days after you enrolled, if that is later than the posted late date. It that is the case include a note about it in the header, including the date that you were enrolled in the class.