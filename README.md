# matInv

Needed to invert a matrix for some relativity problem. It's probably wrong, don't use.

https://blog.c0nrad.io

## Run

```
ts-node index.ts
```

## Sample

```
Trace:
let A =
[ -1, 0, 3
  11, 5, 2
  6, 12, -5 ]
tr(A) =  -1

Mul:
Let A =
[ 1, 2
  3, 4 ]
Let B =
[ 2, 0
  1, 2 ]
A x B =
[ 4, 4
  10, 8 ]
B x A =
[ 2, 4
  7, 10 ]

Pow:
Let A =
[ 1, 2
  3, 4 ]
A^2 =
[ 7, 10
  15, 22 ]

Splice:
Let A =
[ 0, 1, 2, 3
  4, 5, 6, 7
  8, 9, 10, 11
  12, 13, 14, 15 ]
splice(A, 1, 2)
[ 0, 1, 3
  8, 9, 11
  12, 13, 15 ]

det:
Let A =
[ 4, 6
  3, 8 ]
det(A) =  14
Let B =
[ 6, 1, 1
  4, -2, 5
  2, 8, 7 ]
det(B) =  -306
Let C =
[ 1, 3, 1, 4
  3, 9, 5, 15
  0, 2, 1, 1
  0, 4, 2, 3 ]
det(C) =  -4

adj:
Let A =
[ -3, 2, -5
  -1, 0, -2
  3, -4, 1 ]
adj(A) =
[ -8, 18, -4
  -5, 12, -1
  4, -6, 2 ]

inverse:
Let A =
[ 7, 2, 1
  0, 3, -1
  -3, 4, -2 ]
Inverse(A) =
[ -2, 8, -5
  3, -11, 7
  9, -34, 21 ]
A * Inverse(A) =
[ 1, 0, 0
  0, 1, 0
  0, 0, 1 ]
```