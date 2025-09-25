## APCSA
## Esmhan Awadh
## 9/24/2025
## primitives writeup 

### Intro to primitives 

Off the bat, we learn the beginning aspects of Java, which is intensively similar to the JS we learnt last year. Only there are more parts to keep track of in terms of variables and their sizes, methods, and castings. 

#### Challenge 1 

my first challenge came up in lesson 5 activity 2, where we had to use modular division to get each individual integer from a four digit number. My code, which looked something like this, was a clear indicator that i didnt understand that i also needed regular division. 

``` java
      Scanner scan = new Scanner(System.in);
      
      System.out.println("Please enter a four digit number: ");
      int numba = scan.nextInt(); 
      
      System.out.println("Here are the digits: ");
      
      int numbawan = numba%1000;
      int numbatoo = numba%100 %10; 
      int numbatree = numba%10 %10;
      int numbafoh = numba%10;
      
      System.out.println(numbafoh);
      System.out.println(numbatree);
      System.out.println(numbatoo);
      System.out.println(numbawan);
      
```

while the fourth integer came out correctly, the third and second were the same, and the first was every digit but the one i was trying to separate. The solution to my problem was also so simple, because i literally had the groundwork set out, i just needed to incorporate division to cancel out the smaller places. 

``` java

      Scanner scan = new Scanner(System.in);
      
      System.out.println("Please enter a four digit number: ");
      int numba = scan.nextInt(); 
      
      System.out.println("Here are the digits: ");
      
      int numbawan = numba/1000;
      int numbatoo = numba/100 %10; 
      int numbatree = numba/10 %10;
      int numbafoh = numba%10;
      
      System.out.println(numbafoh);
      System.out.println(numbatree);
      System.out.println(numbatoo);
      System.out.println(numbawan);
      

```
