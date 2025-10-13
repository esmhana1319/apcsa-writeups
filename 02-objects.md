## APCSA
## Esmhan Awadh
## 10/13/2025
## objects writeup 

### Intro to Objects: 

Classes create objects; instances of the class that have their own variables and methods. For instance some of the classes we used last unit were ```String``` and ```Scanner```. When we wanted to make a new instance of a scanner, it would look something like this

```java
Scanner scan = new Scanner(System.in);
```
Scanner is the class; scan is the object name; and new is an operator used to make the new instance of the Scanner class. You can tell the difference between classes and primitive data types easily as classes will start with a capital, whilst primitives wont. 

The first things we learned in unit 2 were string concatenation and a deeper look into math. 

```\n``` creates a new line.
```\"``` allows us to include double quotes within a string.
```\\``` is used to print a backslash itself.
```\t``` is used to create a tab (white space).

Some methods that were introduced with String were 
```length()``` Returns the number of characters in a String. The lesson demonstrates how to use this method and highlights the importance of the dot operator and parentheses when calling methods.

```equals()``` Tests if two Strings are equal by comparing their characters. The method returns a boolean value (true or false) based on whether the Strings match.

```substring(int from, int to)``` and ```substring(int from)``` These methods return a subset of the original String, with substring(from, to) specifying a start and stop index, and substring(from) returning the substring from the start index to the end of the String.

```indexOf(String str)``` Searches for a specified String within another String and returns the index of its first occurrence. If the String is not found, the method returns -1.

```compareTo(String other)``` Compares two Strings alphabetically and returns a value indicating their order relative to each other.

Shapes, and other math based methods were also introduced with the concepts of Autoboxing and Unboxing, which were really useful for activity 1 and 2. 

### Challenges 

the first challenge i had this unit was during our first quiz on units 1-4. I got questions 3 and 4 wrong, and in my notes the takeaways i made were: 
q3 = null; 
Explanation - Void means a method doesn't return any value, doesn't refer to objects. Null means empty;nothing 

q4 = sum = 45
Explanation - the 4 and 5 aren't added together manually because its interpreted as a string concatenation

My other challenges came up with activity 2, in which my code kept returning errors because of small typos in variable names that were called in later sections. My most stressful error though was with a small typo in my output, that kept making me fail 3 tests. 

```









