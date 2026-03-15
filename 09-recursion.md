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


```java
public class RecursiveBinarySearch {

    public static int binarySearch(int[] arr, int target) {
        return binarySearch(arr, 0, arr.length - 1, target);
    }

    private static int binarySearch(int[] arr, int low, int high, int target) {
        if (low > high) {
            return -1;
        }

        int mid = low + (high - low) / 2;

        if (arr[mid] == target) {
            return mid;
        } else if (arr[mid] > target) {
            return binarySearch(arr, low, mid - 1, target);
        } else {
            return binarySearch(arr, mid + 1, high, target);
        }
    }
}

```


