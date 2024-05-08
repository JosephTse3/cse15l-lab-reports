# Lab report 3
---

## Part 1 - Bugs
## Task

### Choose one of the bugs from week 4's lab.
### Provide:
  1. A failure-inducing input for the buggy program, as a **JUnit test** and any associated code 
  2. An input that *doesn't* indice a failure, as a JUnit test and any associated code
  3. The symptom, as the output of running the two tests above
  4. The bug, as the before-and-after code change requried to fix it
  5. Briefly describe why the fix addresses the issue

The bugged code that I will be working with:

```
// Returns a *new* array with all the elements of the input array in reversed
  // order
  static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
```
