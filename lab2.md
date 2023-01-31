# Week 4 Lab Report 2
## Part 1
## Part 2
### bug:`reverseInPlace()`

#### failure inducing input: `{5, 6, 7, 8}`
```
@Test 
public void testReverseInPlace1() {
  int[] input1 = {5, 6, 7, 8};
  ArrayExamples.reverseInPlace(input1);
  assertArrayEquals(new int[]{8, 7, 6, 5}, input1);
}
```
#### input that doesn't induce a failure: `{5}`
```
@Test 
public void testReverseInPlace1() {
  int[] input1 = {5};
  ArrayExamples.reverseInPlace(input1);
  assertArrayEquals(new int[]{5}, input1);
}
 ```

#### Symptoms:

failure inducing input: `{5, 6, 7, 8}`

![image](lab2_JUnit_failure.png)

input that doesn't induce a failure: `{5}`

![image](lab2_JUnit_non_failure.png)

#### Before and After:
Before:
```
  static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
    }
  }
```
After:
```
  static void reverseInPlace(int[] arr) {
    int[] newArray = new int[arr.length]; 
    for(int i = 0; i < arr.length; i += 1) {
      newArray[i] = arr[arr.length - i - 1];
    }
    arr = newArray;
  }
  ```
The code that has bug is letting `arr` storing a new reversed array and accessing the old `arr` at the same time. To fix the problem, I created a new array, `newArray`, to store the elements of the reversed `arr`. After the reversed array is stored in `newArray`, `arr` can be the same as the reversed array by `arr = newArray`.
 
## Part 3
Before this week's lab, I have no idea what JUnit was. I always thought I need to have a main method and test my program in the main method. Now that I learned about JUnit, testings are more efficient.