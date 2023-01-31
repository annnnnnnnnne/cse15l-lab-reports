# Week 4 Lab Report 2
## Part 1
## Part 2
### bug:`reverseInPlace()`
Failure-inducing input:
```
  @Test 
	public void testReverseInPlace1() {
    int[] input1 = {5, 6, 7, 8};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{8, 7, 6, 5}, input1);
	}
 ```
## Part 3
Before this week's lab, I have no idea what JUnit was. I always thought I need to have a main method and test my program in the main method. Now that I learned about JUnit, testings are more efficient.
