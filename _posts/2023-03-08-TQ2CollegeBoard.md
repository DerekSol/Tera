---
layout: post
title: MCQ Final Tri 2 Test Correction Blog 
toc: true
categories: [APCSP Week 25]
---

# Test Corrections

**Question 10.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.35.28 PM.png)
When reading this question, I looked at the first answer and thought immediately that this one was the greatest cybersecurity risk out of all. But then after looking over the answers, I realized that emailing your credit card to reserve a hotel can really risk the security of your credit, and would be the most cybersecurity risk out of all of them.

**Question 27.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.37.48 PM.png)
I realized this was incorrect because the distance between two numbers is obtained by taking the absolute value of the difference between the two numbers, not by taking the sum of the absolute values of the two numbers. The correct one is subtracting num1 from num2 and store the result in the variable diff, then take the absolute value of it because it will give the difference as a positive number when done.

**Question 28.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.38.25 PM.png)
I figure that what I got was wrong because the code segment will remove only the first 2 characters of oldString. The right one is A because in order to remove the first 2 characters of oldString, this code segment takes a substring starting at position 3. To remove the last 2 characters of oldString, the substring ends at the position that is 4 characters less than the length of oldString. The right pair for that is C also because the first statement removes the first 2 characters of oldString and assigns the result to tempString. The second statement removes the last 2 characters of tempString and assigns the result to newString.


**Question 35.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.39.13 PM.png)
A is the better answer here because If scoreA is greater than both scoreB and scoreC (the first two IF clauses), then Team A wins. If scoreA is greater than scoreB but not greater than scoreC, then scoreC is greater than both scoreA and scoreB and Team C wins. If scoreB is greater than scoreA (the outer ELSE clause) and scoreC (the IF clause in the outer ELSE), then Team B wins. If scoreB is greater than scoreA but not greater than scoreC, then scoreC is greater than both scoreA and scoreB and Team C wins. Therefore, this would determine that assuming no two team gets the same number of questions right, it will display the team with highest number of questions correct.


**Question 36.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.39.51 PM.png)
II and III will assign the correct letter grade to grade based on the value of the variable score. Going through the options, Code segment I does not work correctly because it is not possible for "C" to be the value of grade at the end of the code segment. Code segment II correctly assigns "A" when the numeric score is greater than 90, or "B" if the numeric score is not greater than 90 but is greater than or equal to 80, or "C" otherwise. Code segment III assigns "C" when the numeric score is less than 80, or "B" if the numeric score is not less than 80 but is less than or equal to 90, or "A" otherwise.


**Question 39.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.40.23 PM.png)
I guessed for this because I was a little confused on how to determine where it goes in the function. After reading the correct answer, it makes sense it will go between line 6 and 7 because inserting this statement between lines 6 and 7 increases the value of count once each time the robot moves forward, which keeps an accurate count of the number of squares the robot visits.


**Question 41.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.40.54 PM.png)
I did not know that in order for binary search to work, the list had to be sorted. That is something that I will now note and is the main reason why I got this question wrong.

**Question 42.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.41.19 PM.png)
I thought that the list containing duplicate elements would effect the binary search because I was not familiar with why this list shouldn't use binary search and what binary search really means. I learned that binary search works on lists that are sorted, so since the elements are not sorted, binary search would not be appropriated.

**Question 47.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.42.01 PM.png)
The answer is spin random, 1-4 since A landing 10 should happen 25% of the time, as well as B landing on 5, and C or D is a total of 50% chance of landing on it. this function will ensure that these percentages are met.

**Question 50.**
![]({{site.baseurl}}/images/Screen Shot 2023-03-08 at 8.43.04 PM.png)
It is algorithm A and D and not B and D because B indicates that the algorithm does not run in a reasonable amount of time. However, for A, As the size of the list grows, the number of steps needed to sort the list grows at a linear rate, as the number of steps is equal to 10n for a list of size n, so the algorithm will run in a reasonable amount of time.


# Test Corrections Reflection
Overall I thought the test was relatively easy to go through and answer to the best of my ability. I felt like I was pretty strong in answering most of the questions, but when it came to terms, definitions, and codes that I didn't know or wasn't really comfortable with, I tend to struggle. I feel like I definitely learned a lot from taking this test and their is a lot of things I still need to learn.