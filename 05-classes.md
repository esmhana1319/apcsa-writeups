## APCSA
## Esmhan Awadh
## 12/7/2025
## Classes Writeup 

### INTRO TO CLASSES 

Unit 5 picks off exactly where we left with our second unit, but gives us a LOT more freedom that comes with big responsibility in a way. 

Some things i especially took note of on my cheat sheet were: 

#### STATIC VS NONSTATIC 
Static - makes certain behaviors or variables of classes accessible through the class that change globally for every instance of that specific class

Non-static - makes certain behaviors or variables of classes inaccessible outside of the class

We specify that a method or variable  is static or non-static depending on whether or not we want it to be global throughout all instances alongside whether or not we want it to be accessible outside of the class via object 

#### INSTANCE VARIABLES 
Instance variables which I'll discuss later in the challenges section along with takeaways, are variables that only occur within a specific instance of an object,  in this case we use this. 

#### PUBLIC VS PRIVATE 
Public and Private determines whether or not a method can be accessed outside of the class within another method. For instance  if we have…

```java 
  public class ClassA {
      private int privateField;
  
         private void privateMethod() {
                   
      }

      public void publicMethodUsingPrivate() {
   
      }
  }
  
  public class ClassB {
  
  }
```

Depending on whether a  method is declared public or private this method can then be called in class B.

#### OVERLOADED METHODS

Something I also took note of was overloaded methods which I found came up on the test and quiz for unit 2 a considerable amount.  overloaded methods can't have different method names, But  must have a different number of parameters order of parameters or type of parameters in order to properly work

#### THIS.
Something I mentioned previously, ```this.``` , can only be used in non-static methods and refers to the specific instance of an object.  For instance if you have an if-statement where you are checking if the current specific instance of an object fulfills the certain Boolean you are calling on it, you can update its value by using this whilst still keeping the same variable name.  


### CHALLENGES
Probably one of my biggest challenges especially during this unit was not taking the easier ways out by using .this and formatting my classes, methods etc in a way that confused private/public, nonstatic/static and different return types so much 

On lesson 5 activity 2, i kept failing tests regarding the oven classes check because of the mistakes i made with the if-statements. Although i managed to make it work without ```this.``` by making my maxTemp = to the maxTemperature in my if-statement, it wouldve been much more merciful to my carpal tunnel if i didnt have to keep respelling it too :(. 
```java
if (maxTemperature > 0 && maxTemperature <= 500){
      maxTemp = maxTemperature;
    }
    else{
      maxTemp = 500;
    }
```
vs. 

if (maxTemp > 0 && maxTemp <= 500){
     this.maxTemp = maxTemp;
    }
    else{
      maxTemp = 500;
    }


My next trouble came during the Unit Exam, where i had the most struggles with questions 8, 10, 11, and 20. 

8. I had a direction, but i didnt consider the fact that the boolean inserted wouldnt be viable if B was smaller than both A and B

10. got the return statement inccorect, voids have NO return type

11. mutator methods directly change the value, not make a new one.

20. the second option wouldnt work in this case because it has the same format as a constructor already present, i thought the name of the variables would combat this but ultimately no

### TAKEAWAYS

1. using .this can save a lot of time regarding updating variables via instance variables

2. keep the De Morgan laws in mind!!! when creating if statements like the ones in coding activity 2 lesson 5 and question 8 on the exam, certain true or false statements will negate else-ifs if not properly understood

3. mutator methods are used to alter your values and will most likely include updating an already existing variable using the parameter made within a method

4. overloaded methods must have a different number of parameters, order of parameters, or type of parameters in order to properly work

