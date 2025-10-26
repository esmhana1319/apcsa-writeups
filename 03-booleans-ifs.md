## APCSA
## Esmhan Awadh
## 10/13/2025
## booleans writeup 

### Intro to Booleans: 
There isnt much to say about java booleans, as theyre the exact same as the ones we learnt in javascript. nonetheless, here are some notes i took on the lessons

* If statement - A conditional statement that runs code only if a condition is true.
* Double equals sign (==) - used to compare two values for equality.
* Selection - decision-making process in algorithms that changes the flow of execution based on a true or false condition.

a new concept i learnt this unit though was De Morgans laws; 

* De Morgan’s First Law - !(A && B) is equivalent to !A || !B.
In Java, if we have a statement like !(x == 5 && y < 15), we can apply De Morgan’s Law to rewrite it as x != 5 || y >= 15.
* De Morgan’s Second Law - !(A || B) is equivalent to !A && !B.
For a Java example, !(x <= 10 || y != 10) can be transformed to x > 10 && y == 10.

for the exam we had to do a lot of touching on this principle; especially when trying to see if different booleans would equate to the same function/output

### Challenges
