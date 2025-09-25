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

### Challenge 2

my second challenge was a similar problem, specifically lesson 6 activity 3, but unlike before i already had some semblance of how to move the integers to the right place and isolaye them. I knew this time we were multiplying and THEN using modular division, but i had used the wrong numbers. 

``` java

    Scanner scan = new Scanner(System.in);
    System.out.println("Please input a decimal number: ");
  
    double dec = scan.nextDouble();
    double newdec = ((double) dec - (int) dec);
    int one = ((int) (newdec * 10));
    int two = ((int) ((newdec * 10) % 100));
    int three = ((int) ((newdec * 100) % 100));
    
    System.out.print("Answer: " + one + " " + two + " " + three);

```

I found that doing the math mentally via the search bar really helped, as it helped me realize that the same process we did in lesson 5 was this problem but division rather than multiplication. 

``` java

Scanner scan = new Scanner(System.in);
    System.out.println("Please input a decimal number: ");
  
    double dec = scan.nextDouble();
    double newdec = ((double) dec - (int) dec);
    int one = ((int) (newdec * 10));
    int two = ((int) ((newdec * 100) % 10));
    int three = ((int) ((newdec * 1000) % 10));
    
    System.out.print("Answer: " + one + " " + two + " " + three);

```
