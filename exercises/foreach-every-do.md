# Foreach-every-do 18.01.2017 exam
Develop an ACSE patch that extends the LANCE language by introducing the foreach construct working as shown in the example below:

```
int a[3] = [1,2,3];
int k = 2;

foreach elem in a {
    ...
} every k do {
    ...
};
```
### Constraints
The construct must check the following things (names refer to previous example):

- The first time it **always** executes the main block.
- **a** must be an array.
- **k** must be an expression evaluating as a number.
- Every **k** iterations, it executes the do block instead of the main one.
- **All** errors should be reported by the compiler.
