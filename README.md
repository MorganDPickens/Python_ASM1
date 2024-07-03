# Python_ASM1
# HW1: Input and Output String : Mad-Lib Game

---

### Policy of Due Dates

If you need additional time to complete this assignment, please contact me before the due date. **No excuses or extensions will be accepted after the due date.** You are allowed up to two extensions: the first extension grants an additional two days, and the second extension grants one extra day. After these two extensions, no further extensions will be permitted, and you must submit whatever work you have completed.

---

### Grading Policy for Uncovered Topics

Avoid incorporating advanced topics or functions that haven't been covered in our studies. The use of uncovered/unfamiliar topics or functions like ChatGPT answers may result in a deduction of points.

---

Your homework is to write a Python program that plays a Mad-Lib game. In the Mad-Lib game, the user is asked for several words of different types (e.g noun, verb, color, adjective). These words are then inserted into a story in a predefined place. The results are a very strange story. If you are unfamiliar with Mad-Libs, you can find more examples on line here: [at madglibs](https://www.madtakes.com/).

For example, here is a simple story that makes sense

> I took my *little* brother to the *store*. While I *bought* *milk* and *apples*, he wanted to *buy* ice cream and candy. Silly *boy*!
> 

The idea is to replace those words in italics and underlined with other words in order to make the story funny/strange/weird. Now, the user doesn't get to see the story, he/she is only asked for 7 different words (to replace the ones identified). The user is prompted with the **type** of each word: the program first asks for an **adjective** , then for a **place** , then asks for a **past tense verb**, then a **plural noun** . For the fifth word, the program might ask for a **fruit** , etc. Once the user enters the words, the program displays the story with the inputted words plugged in. Here is the story with some made up inputs from the above an example story:

> I took my *hairy* brother to the *zoo*. While I *played* *crayons* and *mango*, he wanted to *swim* ice cream and candy. Silly *lizard*!
> 

---

---

### Homework Specifications

- Preliminary planning:
    - Make up a short story (or borrow a story from tv, film, book, etc). It must contain at least 3 sentences. Write it down.
    - Go through it and choose at least 6 words that you want substituted with the user's input. (At least 2 words from each sentence). Identify what types of words these are: for example they could be nouns, adjectives, proper names, verbs, past tense verbs, or something more specific, like fruit or color or sport, anything you want.
- Program requirements:
    - Your python filename should be “yourLastNameHW1.py”. For an example, my last name is “suk” so my filename should be “sukHW1.py”.
    - When your program starts, have it print a message to welcome the user to your game.
    - Next, the program prompts the user for each word, one at a time. Make sure the program tells the user what type of word to enter with each prompt.
    - Once the user has entered the last word, the program should print the story with the user's words inserted into the story in the correct places.
    - Avoid lines wrapping in the Shell window. When I run your program, I do not resize the Shell window. You can do this by keeping lines of code <= 80 characters long. You can also do this by including the newline character, '\n', in your print() statements.
- Documentation and Style Requirements:
    - Make sure to refer to the Documentation and Style Guidelines in Canvas. You can find this under Course Resources and linked on the homework page.
    - Keep all lines of code and comments <= 80 characters long.
    - When writing comments, assume the reader has not read this homework page.
    - Include a comment at the top of your file that contains your name, date, and a program description.
    - The comment at the top of the file should also contain the original story; in other words, the original text before any words get replaced.
    - Include blank lines between program sections (like input and output) and other comments within your code so that it is easy for me to read
    - Choose good variable names

### Written Report

Include a comment block at the ***end*** of your program with a short written report addressing the following questions.  Part of the grade is based on the effort put into your reflection of your process.  Remember to use proper punctuation, capitalization, etc. as you would for any college-level writing.

- How did you go about starting this assignment? How did you come up with your story?
- How did you test your program? What works and what doesn't?
- What did you learn from this assignment? What would you do differently next time?

### Grading

The following table shows the rubric of grading HW 1. 

| Criteria | Rating | Point |
| --- | --- | --- |
| Program runs correctly | Introduction : 1 pt
Prompt for inputs : 4 pt
Output with story with user’s inputs : 4 pt
Display is within the size of the shell : 1 pt | 10 pt |
| Comments and Style | 5 pt : Completed
2 pt : Basic comments
0 pt : No comments on your program | 5 pt |
| Written Report/Reflection | 5 pt : Completed
2 pt : At least, 1~2 sentences
0 pt : No written report | 5 pt |
| On-Time Submission | 50% reduction after the due date | 0 pt |
