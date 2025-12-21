## APCSA
## Esmhan Awadh
## 12/7/2025
## Arrays Writeup 

### INTRO TO ARRAYS 

Unlike booleans and iteration, i found that arrays in java were quite different in comparison to the ones we used in javascript, alongside their fundamentals too. 
The way an array is built is via an object: but they can hold both object and primitive values 

```java
String[] cats = new String[3]; 
```

The type of values that are held in the array are determined by the first part and leaded by [], then the name of the array alongside a value for how much indexes it should have 

Another method would look something like this 

```java
String[] cats = new String{"sunshine", "mickey", "harry"};
```

specific indexes, which start with 0 first and foremost, can be directly changed or singled out by calling the arrays name alongside the position the value is at. It was extremely important to note on both the quiz and the final exam that the data type of the value can play important factors on how it appears in a boolean, method, or iteration. 

### Challenges 

1. My first challenge came with our very first quiz, but was ultimately quite silly.

   <img width="700" height="199" alt="Screenshot 2025-12-21 at 5 46 49 PM" src="https://github.com/user-attachments/assets/dad52757-ab23-40df-aa82-2d33d62e6679" />

   Ultimately, remembering the importance of index value vs index position was something that i struggled with for a little on some of the fast start quizzes due to reading questions too quickly, so in hindsight i shouldve seen this coming

2. FRQ 6: For once, ideas for what to write in the frq practice came really easily, but something i did that got a lot of points taken off for the first part was creating unnecessary variables. I thought i needed to create a variable to count for employees within my loop, but that was formatted in a way where the order didnt account for how this count would be updated for all values except the max and min. According to the rubric a canonnical solution would look like this: 
   
<img width="387" height="313" alt="Screenshot 2025-12-21 at 6 00 15 PM" src="https://github.com/user-attachments/assets/5fba74c1-91dd-4c89-a270-72a673db3a96" />

3. My last challenge this unit came via the final exam with questions 3, 8, and 20.

  the correct answer for three was: 
<img width="251" height="135" alt="Screenshot 2025-12-21 at 6 02 19 PM" src="https://github.com/user-attachments/assets/26f9a8aa-48cc-49b8-8afd-03d7142694a6" />
  because we are trying to print numbers divisible by three rather than the indices 

  the correct answer for eight was: "Returns true if each element of the array is greater than the element after." as false is returned only if the selected element is less than the previous; making sure the array is in ascending order 

  the correct answer for twenty was: "12" as 
