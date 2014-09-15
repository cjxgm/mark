## a <= b DOES NOT EQUAL TO !(b < a)

> example:
```c
for vector a and b,
a < b: a[0] < b[0] && a[1] < b[1]
!(b<a): a[0] <= b[0] || a[1] <= b[1]
a <= b: a[0] <= b[0] && a[1] <= b[1]
```
