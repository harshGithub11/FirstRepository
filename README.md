# FirstRepository
Learning to use Github - Creating first Repository
## Problem Statement:

```
1. You are given a string str of digits. (will never start with a 0)
2. You are required to encode the str as per following rules
    1 -> a
    2 -> b
    3 -> c
    ..
    25 -> y
    26 -> z
3. You are required to calculate and print the count of encodings for the string str.

     For 123 -> there are 3 encodings. abc, aw, lc
     For 993 -> there is 1 encoding. iic
     For 013 -> This is an invalid input. A string starting with 0 will not be passed.
     For 103 -> there is 1 encoding. jc
     For 303 -> there are 0 encodings. But such a string maybe passed. In this case
     print 0.
```

---

- Have done this question in recursion as well.

## Consider this String: "0212010100"

(Though in the pepcoding's question a string will not be starting with zero but let's consider this case as well.)

Let's talk about the base case if a string starts with zero then, there will not be any possible encoding as for zero we don't have any encoding, So the answer will be zero.

### Let's define the meaning of the storage:

- dp[i] will store the number of encodings for the String starting from index 0 till i.

### Direction of the problem:

- String from index 0 till 0 will be the smallest problem.

### Travel and Solve:

Start from index 0 and traverse till the last index of the string.

## Now for String: "212010100"

- Now for the first character of any String the no of possible encodings will always be 1 (other than the base case discussed above). So **dp[0]** will always be 1.

### Highlight of the problem:

We will have to think for four cases in this question:

- 0 0
- 0 X
- X 0
- X X

where X represents any digit between 1.

---

**Solution Video :** 

[https://www.youtube.com/watch?v=jFZmBQ569So](https://www.youtube.com/watch?v=jFZmBQ569So)

---

Code: 

```java

```
