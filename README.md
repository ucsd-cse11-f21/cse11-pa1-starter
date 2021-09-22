# CSE 11 Programming Assignment 1

### Due Dates: Tuesday, October 5, 10:00PM Pacific Time

## Learning Goals
- Set up and test your Java development environment
- Write functions that take integer parameters and return integer results.
- Practice using design recipes

## Collaboration
Different assignments in this course have different collaboration policies. On this assignment, you can collaborate with **anyone in the course**, including **sharing code**. In your submission, give credit to all students and course staff who helped you with this assignment by noting their name and how you used their ideas or work. Note that using someone's work without giving credit to them is a violation of academic integrity.

## Part 1- Setting Up
- **On your own computer**: General instructions for setting up your environment can be found in [this](https://github.com/CSE11-SU121-Assignments/cse11-pa0.5-Setup-starter/blob/main/Instructions%20for%20setting%20up%20Java%20on%20your%20own%20machine.pdf) document, and as video tutorials for [Windows](https://drive.google.com/file/d/1FxIAaGj7JAAN5QNpqcx1JBdv36yzX6TX/view?usp=sharing)  and [Mac](https://drive.google.com/file/d/1EsF6t_ZA7TIdQ0iIu9X_dh1T5YGmzxNG/view?usp=sharing).
- **In the CSE Labs**: Watch and follow the instructions from this video: [LINK]
- If you get stuck at any point, do any one of the following:
    - Take a screenshot and ask on Piazza! (Not sure how to take a screenshot? Try Googling it for your particular platform, like “screenshot microsoft windows” or “screenshot chromebook” or “screenshot os x”, or ask how on Piazza and we can help.)
    - Join a [help session](https://ucsd-cse11-f21.github.io/staff-and-help.html)!
    
- If you get stuck, can't get help, and can't finish, write up a description of what you tried and why you couldn't finish! We'll give you credit for that, too, and it will help us understand how to help you get set up.


## Setup
Follow the instructions in the video tutorial for your chosen environment (Windows, Mac, or CloudLabs) to set up your environment for writing code in Java (including your Java version number). You can also use this document for your reference. Write a few sentences describing which environment you will be using, and the steps you took to set it up. Note that you're free to use another environment if you like, we just don't have tutorials for other environments.

## Running Code

Create a new directory named pa05. Create a new file in pa05 named:
`IntroductionTo.java`
Put the following code into that file (you can copy-paste):
```
class FirstExample {
  int theNumberFive = 5;
}
```
Compile and run your program. You can find instructions for "Editing Your Java Code" and "Running Your Java Code" [here](https://github.com/CSE11-SU121-Assignments/cse11-pa0.5-Setup-starter/blob/main/Instructions%20for%20setting%20up%20Java%20on%20your%20own%20machine.pdf). Instructions are also included in the setup video tutorials for [Windows](https://drive.google.com/file/d/1FxIAaGj7JAAN5QNpqcx1JBdv36yzX6TX/view?usp=sharing) and [Mac](https://drive.google.com/file/d/1EsF6t_ZA7TIdQ0iIu9X_dh1T5YGmzxNG/view?usp=sharing). Finally, take a screenshot of your terminal (including the commands you ran to compile and run the code) and include it in your [writeup](https://github.com/CSE11-SU121-Assignments/cse11-pa0.5-Setup-starter/blob/main/PA0.5%20Submission%20Template.pdf).

[Word version of the template](https://github.com/CSE11-SU21-Assignments/cse11-pa0.5-Setup-starter/blob/main/PA0.5%20Submission%20Template.docx).




## Part 2 - Writing Methods
- You can download the starter code for this assignment by downloading this repository and navigating to the ```pa1``` folder. 
- You will write your code in DesignRecipeExamples.java. You can run the code to test it yourself with:

    Mac and Lab:     ```./run DesignRecipeExamples```
    Windows:         ```.\run.bat DesignRecipeExamples```
- For problem 3 and 4, you will use the following design recipe:
    1. Write the method header
    2. Write a short comment documenting the method (including assumptions, like if a parameter should take values only in a certain range)
    3. Write 3 examples of calling the method
    4. Write the method body
    
    Using this recipe for problems 1 and 2 is optional, but highly encouraged.

## Submission
- Your submission will entirely be in the file ```DesignRecipeExamples.java``` which you will upload to Gradescope for the PA1 assignment.
- You should see your grade for the autograded portion of the assignment after submission. If you see an error message instead, you can make a private post to the instructors on Piazza.

*(Several of these examples are borrowed from [How to Design Programs](http://www.htdp.org/2003-09-26/Book/curriculum-Z-H-6.html#node_sec_3.3), and its [Supplemental Material](http://www.htdp.org/2003-09-26/Problems/2.html))*

## Problem 1: Perimeter 
Develop a method named ```perimeter``` that when given the width and height of a rectangle will return its perimeter.

The rubric we will use to grade this method is:

- The method has a correct header (parameters and return type)
- The method has a correct method body
- There are at least two examples of calling the method with different arguments, commented with their expected values
- You can show your program running and the expected values are produced

## Problem 2: Border Area
Develop a method named ```borderArea``` that given a width and height describing a rectangle, and another width and height describing a rectangle cut out of the center of the other, returns the area of the region between them. For example, the blue area in this shape:

<img width="270" alt="Q2_example" src="https://user-images.githubusercontent.com/25071081/112794129-4620bf00-901b-11eb-98a9-58b31327f6e2.png">

- The method has a correct header (parameters and return type)
- You can explain what each parameter means in terms of which rectangle it refers to and whether it refers to width or height
- The method has a correct method body
- There are at least two examples of calling the method with different arguments, commented with their expected values
- You can show your program running and the expected values are produced

## Problem 3: Converter 
### Implementation
Develop a method (with a name of your choice!) that takes one int parameter, converts it to another int value, and returns the new int value. For example, your function could convert:
- Fahrenheit to Celsius
- between currencies

Write a comment for your method, describing what it does and what parameter it takes. If you use any outside sources for the conversion, be sure to cite those in the comment as well.

### Testing
Call your method on at least 3 different examples. Compare each result against a reference converter (Many search engines have built-in converters, or you can use a calculator) and add a comment above the function call to discuss differences (if any) that you get between your program and the reference.

- The method has a correct header (parameters and return type)
- You can explain what the parameter means, and if there are any nonsense values (for example, a negative amount of rainfall in inches)
- The method has a method body that matches the examples you chose
- There are at least two examples of calling the method with different arguments, commented with their expected values
- You can show your program running, the expected values are produced
- You can justify the output based on an external source or your own design description

## Problem 4: Combiner 
### Implementation
Develop a method (with a name of your choice!) that takes at least two int parameters, combines them to another int value, and returns the new int value. For example, your function could combine:
- Feet and inches into total in inches
- Starting hour and minute and end hour and minute into total number of minutes

Write a comment for your method, describing what it does and what parameters it takes. If you use any outside sources, be sure to cite those in the comment as well.

### Testing
Call your method on at least 3 different examples. Can you call your method with arguments that run, but produce an incorrect output? Call your method with at least one such pair of arguments, and add a comment above it explaining why the output is incorrect. If you cannot find such a pair of arguments, write a comment explaining why you believe no such input exists.

- The method has a correct header (parameters and return type)
- You can explain what the parameters mean, and if there are any nonsense values
- The method has a method body that matches the examples you chose
- There are at least two examples of calling the method with different arguments, commented with their expected values
- You can show your program running, the expected values are produced
- You can justify the output based on an external source or your own design description


## Submission

Your submission will be in a few parts.

1. First, in the form of a PDF writeup demonstrating your setup. You can find a template for the writeup [TODO link to Google Docs] [here](https://docs.google.com/document/d/1wGIw0DH433jikfImoTUZZGMU9kTOzIf3/edit?usp=sharing&ouid=101937787285726759641&rtpof=true&sd=true). You will submit the PDF you create Please submit your writeup to the [PA1 PDF assignment](FILL).
2. Second, in the form of a code submission of your program with the methods you wrote for part two, at [PA1 code gradescope assignment](FILL).

To get your work graded, come to any [remote help hours session](https://ucsd-cse11-f21.github.io/staff-and-help.html) after submitting both Gradescope assignments. A tutor will grade and give you feedback on your work live, and tell you anything you need to fix to get full credit.

## Grading

To earn a **2**:
- Demonstrate via screenshots in your PDF a working setup of Java either in labs or on your own computer
- Answer all questions in the PDF submission
- Complete all checklist items for all methods

To earn a **1**, submit something but miss some items from **2**
