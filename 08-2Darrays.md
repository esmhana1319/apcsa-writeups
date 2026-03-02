## APCSA
## Esmhan Awadh
## 12/7/2025
## Two Dimensional Arrays Writeup 

### INTRO TO 2D ARRAYS

To my misfortune, two dimensional arrays were something that I already had a significant exposure to prior to this unit because of tensors. The great news on the other hand, was that they were a much easier concept to comprehend. They are essentially arrays within arrays that can sort through information like score data, gameboards (evil sep battleship), and spreadsheets. They were also something i saw instances of when creating my previous years freedom project with in kaboom. 

The way you can write a two dimensional array looks something like this 

```java
int nums[2][3] = { {1, 4, 2}, {3, 6, 8} };
```
The [2] would point to the amount of rows there are and the [3] would point to the amount of columns. This is something I had to vigorously inject into my brain, because very frequently on the AP classroom practice would I mix up the two as well as point to entirely incorrect data. 

There are two ways to loop through two dimensional arrays, Row Major and Column Major which really only varies on how the array is iterated through.
```java
int[][] nums = { {1, 4, 2}, {3, 6, 8} };

for (int row = 0; row < matrix.length; row++) { 
    for (int col = 0; col < matrix[row].length; col++) { 
        System.out.println(matrix[row][col]);
    }
}
```

```java
int[][] nums = { {1, 4, 2}, {3, 6, 8} };

for (int col = 0; col < matrix[row].length; col++) { 
    for (int row = 0; row < matrix.length; row++) { 
        System.out.println(matrix[row][col]);
    }
}
```
Theres also an evil third way, which Ill talk about later because it appeared in a question I got wrong and presented for test credit 

```java 
for (const row : nums) { 
    for (const num : row) { 
        console.log(num);
    }
```

### CHALLENGES 

1. <img width="827" height="563" alt="Screenshot 2026-03-01 at 9 14 57 PM" src="https://github.com/user-attachments/assets/f944286a-067d-4e23-a75f-96271f8eda36" />

This third question on the AP Classroom review was something that opened my eye to a struggle I had to touch on before the exam. I had answered 15 which came out as incorrect but there was little to no explanation as to why. When I looked further I realized that I was adding up the row, not the column. I looked down at my cheat sheet for the exam that day and then also realized that the examples that I had written were, too, also swapping the col and row. With some quick reminders from Xin and Kiara, I debreifed the question with them and also corrected my own resource for the test. 

2. The two exam questions I had gotten incorrect were also something I sought to touch up on. 
<img width="595" height="505" alt="Screenshot 2026-03-01 at 9 19 45 PM" src="https://github.com/user-attachments/assets/5447913f-cb4c-49b6-91a4-d1235e917bea" />
<img width="591" height="474" alt="Screenshot 2026-03-01 at 9 19 36 PM" src="https://github.com/user-attachments/assets/959b7463-787a-4445-8a03-7df74d9dd5bb" />

  18. <img width="271" height="112" alt="Screenshot 2026-03-01 at 9 22 14 PM" src="https://github.com/user-attachments/assets/b583b8e4-8c9c-42fc-9633-f1f6df1563be" />
      Ultimately the reason why this would point to the correct answer is because it states that if the current iterated value is less than the value saved as the current minimum, it would update the value and the result variable to point towards its respective column; this is why its important to read questions, because not only did i interpret it entirely opposite, but i also rushed myself out of stress to complete my test in time

  20. <img width="273" height="88" alt="Screenshot 2026-03-01 at 9 25 52 PM" src="https://github.com/user-attachments/assets/afa18304-7b08-4c45-9a9d-6ef79352bdd3" />
    the reason why this answer was correct was because the variable num itself pointed to the correct variable that represented the current iterated value; if this value was less than the minimum it would be updated to num.

3. Presentations
     I tried to take my takeaways from last time and breifly explain during the debreif while saving time and capturing important details, but one thing I should totally improve for next time is trying to better focus on the bigger aspect of the problem to properly clear up what people who are also confused about the problem have trouble with. Also try to not get distracted or sidetracked with silly stuff :0


### TAKEAWAYS 

1. Remember [row][column]
   rows are horizontal, columns are vertical essie

2. ``for (double num : mat[k])`` means that the variable num points to every cell/element within the loop. these kind of for loops are a great shortcut to remember, but also its fundamental to understand that the value of num will not point to any index like i thought it did before

3. Take your time trying to understand what the question itself is asking for aswell as what the options do rather than try to understand how it works; do not rush this  


