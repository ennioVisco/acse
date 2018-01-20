# Foreach-every-do 18.01.2017 exam
Develop an ACSE patch that extends the LANCE language by introducing the foreach construct working as shown in the example below:

```
int a[3] = [1,2,3];
int k = 2;

foreach elem in a {
    ...
} every k do {
    ...
}
```
### Constraints
The construct must check the following things (names refer to previous example):

- **a** must be an array.
- **k** must be a number.
- **All** errors should be reported by the compiler.
