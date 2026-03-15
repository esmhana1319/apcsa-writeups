## APCSA
## Esmhan Awadh
## 3/15/2026
## Recursion

### INTRO TO RECURSION

The way I dumbed down recursion for myself was through comparing it to cleaning dishes. Hypothetically, if i were to ask a robot to do them for me, theyd run the same recursive program to clean until a base case of no dishes being left in the sink. The problem with this analogy is that its farfetched; a more accurate one would be the fibonacci sequence, that recurs infinitely in real life. It was one of the first examples of recursion we learned to code and looks something like this

```java
public int fibonacci(int n)  {
    if(n == 0){
        return 0;
    }
    else if(n == 1){
      return 1;
    }
    else{
      return fibonacci(n - 1) + fibonacci(n - 2);
    }
}
```

if the base cases arent met, the function calls itself again, meaning recursive functions can be used in place of basic loops required for sorting and searching for indexes or values. For instance, Binary search algorithms


```
