#asgn04-483f17-pitest-acts
CS483: Software Testing
Homework Assignment #4 	 Assigned: Tuesday Nov 20, 2017
Total Points: 100				Due: Sunday Dec 03, 2017 11:55PM

# Objective: Comparing structural coverage, mutation testing, and combinatorial testing
The objective of this assignment is to get you to compare the effectiveness of structural coverage based unit testing, mutation testing, and combinatorial testing. Our target program will remain the same vending machine program that we had worked with earlier in Assignment 01 and a new Triangle Program.

Clone the project pitest-acts-exercise from this repository in github: https://classroom.github.com/a/c9DcnM2r

There are two packages in the project; namely triangle and vendingmachine. 

You will do this assignment in three steps:

# Step 1: Revisit Unit Testing and Simple Statement Coverage
1.	Write thorough unit tests using Junit for the Triangle program. You are free to make some modifications to the Triangle program to make it easier to test. 
2.	You are also free to make small modifications to the vending machine program to make it easier to test. Update your test cases from assignment 1 with more unit tests, if necessary. Otherwise, you can simply work with your old unit tests that you had written. 
3.	Run EclEmma (Structural Coverage).
4.	Take snapshot of the coverage from eclipse.  

*Writeup-1:* As part of your report to submit, write what changes, if any, you made to the code. How did the changed code help you test the program better. Create a table with details of the statement and branch coverage you are receiving for each of the classes. This information is produced by the code coverage tool EclEmma that you are running. I just want you to summarize it nicely in a table format in your writeup. 

# Step 2: Using Mutation Testing with Pitest
1.	Run the Pitest or MuJava on your program and unit tests. 
    1. The Pitest eclipse plug-in  is available at https://github.com/philglover/pitclipse
    2. You will find MuJava at https://cs.gmu.edu/~offutt/mujava/
    3. Take a screen shot of the summary output. Include it to your report. Also, write in your report, what pecr
3.	If you are using Pitclipse, take a screen shot of the PIT Mutations window and add that to your report. This window has all the mutations that were used, and which ones succeeded and which ones failed. If you use MuJava, try to get the equivalent information from the MuJava Report. 
4.	What is the overall strengths of your test suite based on the Mutation Score (Mutation Coverage)?
5.	Identify three interesting mutations from different places that did not get killed. 
  1. Write in detail, why those mutations were not killed by your unit tests?
  2. How could you have updated your Junit tests in that your tests would have killed those mutants?

*Writeup-2:* Write a reflection of what have you learned about how to effectively you design your test cases. 

# Step 3: Using Combinatorial Testing with ACTS

1.	Use the NIST’s combinatorial testing tool, ACTS to design some input model for the Triangle program. Get two-way combinations from the input-model to test you program.  Update your units tests for the triangle program including the results of the combinatorial testing model.

2.	Design another input model for testing the vending machine program. 
  1.	Generate both two-way and three-way combination of the input model. Use the two-way combinations to test your vending machine program. To do this, you will use the outputs of the 3-way combinations and use them in your unit test code. 

*Writeup 3:*
Describe what was the rationale behind the design of your input model? How did you decide on the different fragments (variables) to create the combinations? How did you decide to choose the different values for each fragment (variable)?

3.	Repeat the Step 1 Statement coverage and Step 2 mutation coverage with the updated test suite for both the triangle and the vending machine program.

*Writeup 4:*
  1. How has the coverage changed?
  2. Write a reflection writeup of what you have observed in this exercise?
 
*Writeup 5:*
  3.	What do you think are the strengths and weaknesses of selecting test cases based on statement coverage vs. mutation score vs. combinatorial approach?
  4.	Can you discuss the costs associated with each of the approaches? 
