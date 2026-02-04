## APCSA
## Esmhan Awadh
## 12/7/2025
## ArrayLists Writeup 

### INTRO TO ARRAY LISTS

My First exposure to arraylists happened when i was studying for the unit 6 exam, and accidentally came across a video on arraylists which i ended up taking notes on thinking they were Unit 6 arrays. The first thing i noticed about arraylists, after i realized i was cramming the wrong unit, were that they were extremely similar conceptually to the ones we learned in SEP11; just instead of push and pop we had different inbuilt methods that enabled us to get, set, and remove the values within specific indices. 


The way youd make a basic array list is something like this
```java
import java.util.ArrayList;

public class Main {
  public static void main(String[] args) {
    ArrayList<String> cats = new ArrayList<String>();
    cats.add("sunshine");
    cats.add("mickey");
    cats.add("harry");
    cats.add("samantha");
    System.out.println(cats);
  }
}

```
The different thing about arraylists in contrast to java arrays is that they are *resizeable*, meaning they dont need to have a predefined size and can be made smaller or bigger according to the methods being used. They are also overall an easier way to store and manipulate information in my opinion </3 

The other different thing about arraylists is that we dont use .length to get their size, but rather .size(). 

### CHALLENGES 

The thing i had the biggest challenge with was our final exam, aswell as our presentations for debreif; ill go over why i was wrong for a couple of incorrect questions, and then ill give my input on how i presented them to my peers and what i learned in the process. 

<img width="571" height="309" alt="Screenshot 2026-02-04 at 7 26 12 AM" src="https://github.com/user-attachments/assets/cbdf5f2a-f03c-4bda-8dac-43404c931802" />

For this question, i ultimately chose this answer; which was wrong as the method is literally looking to see whether the battery is fully charged or not; and something ill mention a lot later on is that i made some silly mistakes from not reading close enough.  

<img width="530" height="223" alt="Screenshot 2026-02-04 at 7 26 57 AM" src="https://github.com/user-attachments/assets/17a2bc58-3b58-4001-8e3a-e36f4555ba02" />

For this question on the other hand, i didnt take into consideration what the final outcome for each would be, and how it solidified the objective of the code. I assumed that because the statement would remove any duplicates, that it worked for all list pairs; it did not 
<img width="579" height="483" alt="Screenshot 2026-02-04 at 7 29 09 AM" src="https://github.com/user-attachments/assets/dd3760db-e2de-4ee7-8e03-2329793cd1d9" />

For this question, i incorrectly did my process of elimination, aswell as misunderstood what the third change would do. The third change incorrectly sorts the values to higher indices rather than lower ones; Although i understood that the second change was correct, i didnt see the inherent problem with the third and first together. 
<img width="586" height="595" alt="Screenshot 2026-02-04 at 7 30 39 AM" src="https://github.com/user-attachments/assets/cb97f9c0-ef22-47bd-8611-0efa95e15b9f" />

For my presentation for the last two of the questions i went over, i tried targetting specific parts of the problem and methods i used to better understand its context. I think this worked well in getting the point across, but something i noticed i struggle with is delivering information at a good pace. Sometimes i take too long to explain something that may or may not be irrelavent and lose time to explain the next parts; for the future, that is something ill pay attention to. 

### TAKEAWAYS 
