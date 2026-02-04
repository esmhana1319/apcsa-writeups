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





