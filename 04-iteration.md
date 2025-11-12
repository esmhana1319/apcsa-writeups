## APCSA
## Esmhan Awadh
## 10/13/2025
## loops writeup 

### intro to loops

The thing about loops in java is that they are the exact same as the ones we learnt with javascript in sep11, so this unit was not only a good refresher to how they worked, but also a great way to deepen my understanding of what i can do with loops aswell as a great level up of my ability to write embedded loops. 

* for loops - with for loops, we can define not only when it runs but when itll stop; we do this when we want to control how much the loop iterates
* while loops - with while loops, we define it by bounds that the user defines; we do this when we dont know how much the loop will iterate

#### how to loop through strings 
looping through strings has a very similar look to the for loops we were using last year, where we define a variable (i or j usually) and make it equivalent to each character in the string, in which i is less than the length of the string and increases per loop. 

#### nested loops
the way i remembered how nested loops worked was via multiplication, but later on i found that using python tutor to visualize the order really helped in understanding how many times the steps would iterate. 

```java
for (int i = 0; i < str.length(); i++){
      for(int j = 0; j < num; j++){
        System.out.print(str.substring(i, i + 1));
      }
    }
```

for instance, this nested loop from activity 1 in lesson five. The middle code will iterate the amount of times the user inputs, in my case 3 times. But in total, the middle code will iterate however many characters are in the string multiplied by the number the user inputs. Say i put a four letter word and the number three, the code will iterate a total of 12 times.

### Challenges 

1. my first challenge came with our quiz on lessons 1-3. I got 5/10 correct, and when checking my annotations for the thought process i had answering the questions, i found that i eliminated two obviously wrong options, but chose the wrong out of the possible two. for instance
   * i got 3. wrong because i didnt acknowledge that using < instead of <= would eliminate the needed output of 15
   * i got 9. wrong because i didnt acknowledge that option I would print an unnecessary output of 45
In other words, from this i found that i needed to create a deeper understanding of HOW these loops iterate via comparing outputs and singling out the correct option
2. My second challenge came with activity 2 on lesson 5. Although my output was correct, i was still recieving a 50. After checking my code with python tutor, i removed a space from my last line out of curiousity, which gave me the needed 100%.
   ```java

   import java.util.Scanner;

public class U4_L5_Activity_Two
{
  public static void main(String[] args)
  {

    for (int i = 10; i > 0 ; i--){
      for(int j = 0; j < i; j++){
        System.out.print(i + " ");
      }
       System.out.println(" "); /* space between quotes made unecessary output; once removed the code passed both tests */ 
    }
    
  }
}
```

### takeaways

1. trace tables are necessary in tracking the outputs of your loops, and are very useful in determining how a <= or < can affect your output. After practicing tracetables, i did significantly better on the final exam 
2. Python tutor is a great way to visualize loops, for a lot of the questions i struggled with during reviews, i used python tutor to check if my trace tables were correct; overtime this made my answers quicker which is great
3. unecessary code can make you struggle with a lot of tests; sometimes the shortest solution is the best, which is where comparing inputs with trace tables is once again important in determining the best solution. 

