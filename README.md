# What Sucks Most

## a <= b DOES NOT EQUAL TO !(b < a)

> example:
```c
for vec2 a and b,
a < b: a[0] < b[0] && a[1] < b[1]
!(b<a): a[0] <= b[0] || a[1] <= b[1]
a <= b: a[0] <= b[0] && a[1] <= b[1]
```

# Windows Sucks
http://www.peterstock.co.uk/games/mingw_sse/
sse + mingw, default compilation flag == bug
