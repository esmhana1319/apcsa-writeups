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

My first challenge, which came up during our final activity for unit 3 was in relation to comparing strings. For whatever reason, even if two strings were equal, the if statement would automatically output the else statement. 

```java
if (answer == "yes"){
      System.out.println("pass test");
    }
    else{
      System.out.print("fail test");
    }
```
The reason this wouldnt work though, was because unless the strings being compared point to the same reference, they will fail the test for equality. What i really needed to do here was use ```equals()``` and input the string "yes" to compare the strings properly. 

```java
if (answer.toLowerCase().equals("yes")){
      System.out.println("pass test");
    }
    else{
      System.out.println("fail test");
    }
```
My second challenge came up on our final exam; i got two questions wrong, for rather silly reasons in my opinon 

5. The following if statement determines the amount of customers that come in at the Java Restaurant. It uses the double variables low, amount and high.
```java
if (low < amount  && amount < high)
{
  System.out.println("Amount of customers could be better.");
}
else
{
  System.out.println("Amount of customers is great!");
}
```

For this question i answered two on the basis that it worked like one but didnt have the extra great outcome; i think where i got confused here though was that in the original solution, when the amount of customers was higher or lower it was great, but inbetween could be better. The first option would be the only one that has the exact same function and output. 

13.Consider the code:
```
if (a != b || c < d)
```
Which of the following is an example of short circuit evaluation?

For this question, i answered "if a != b is false it evaluates c < d" on the basis that i read it incorrectly; which admittedly i was salty about but its a great reminder to read the solutions im picking carefully to make sure theyre the correct ones. 

### Takeaways 
