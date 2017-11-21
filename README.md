#asgn04-483f17-pitest-acts
CS483: Software Testing
Homework Assignment #4 	 Assigned: Tuesday Nov 20, 2017
Total Points: 100				Due: Friday Dec 01, 2017 11:55PM

# Objective: Comparing structural coverage, mutation testing, and combinatorial testing

The objective of this assignment is to get you to compare the effectiveness of structural coverage based unit testing, mutation testing, and combinatorial testing. Our target program will remain the same vending machine program that we had worked with earlier in Assignment 01. 

Clone the asgn04-483f17-pitest-acts from the course repository in github. There are two packages in the project; namely triangle and vendingmachine. 

You will do this assignment in three steps:

# Step 1: Revisit Unit Testing and Simple Statement Coverage
1.	Write thorough unit tests using Junit for the Triangle program. 
2.	Update your test cases from assignment 1 with more unit tests, if necessary, for the vending machine program. Otherwise, you can simply work with your old unit tests that you had written. 
3.	Run EclEmma (Structural Coverage).
4.	As part of your report to submit, create a table with details of the statement and branch coverage you are receiving for each of the classes. Take snapshot of the coverage from eclipse.  

# Step 2: Using Mutation Testing with Pitest
1.	Run the Pitest on your program and unit tests. 
2.	Take a screen shot of the summary output. Include it to your report. 
3.	Take a screen shot of the PIT Mutations window and add that to your report. 
4.	What is the overall strengths of your test suite based on the Mutation Score?
5.	Identify three interesting mutations from different places that did not get killed. 
a.	Write in detail, why those mutations were not killed by your unit tests?
b.	How could you have updated your Junit tests in some ways so that your tests would have killed those mutants?
6.	Write a reflection pWhat have you learned about the how you designed

# Step 3: Using Combinatorial Testing with ACTS

1.	Use the NIST’s combinatorial testing tool, ACTS to design some input model for the Triangle program. Get a two-way combinations from the input-model to test you program.  
2.	Design another input model for testing the VendingMachine Program. 
  1.	Generate a three-way combination of the input model and use them to test your vending machine program. To do this, you will use the outputs of the 3-way combinations to write your unit test code. 
  2.	What was the rationale behind your input model?
3.	Repeat the Step 1 Statement coverage and Step 2 branch coverage with the updated test suite.
  1. How has the coverage changed?
  2.	Write a reflection writeup of what you have observed in this exercise?
  3.	What do you think are the strengths and weaknesses of selecting test cases based on statement coverage vs. mutation score vs. combinatorial approach?
  4.	Can you discuss the costs associated with each of the approaches? 
