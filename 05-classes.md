## APCSA
## Esmhan Awadh
## 12/7/2025
## classes writeup 

### intro to Classes 

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


