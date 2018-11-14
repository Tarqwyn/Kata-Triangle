
This test is all about finding the shortest route. Given we have triangle, find the shortest path expressed as a *sum* of the values from top to bottom. At each step you may move to *adjacent* numbers on the row below.

For example, given the following triangle as an array.

```
var triangle = [
     [2],
    [3,4],
   [6,5,7],
  [4,1,8,3]
]
```

The minimum path sum from top to bottom is 11 (i.e., 2 + 3 + 5 + 1 = 11).

Your code should work with the following test cases..

```
triangle1 = [
     [1],
    [4,3],
   [8,2,6],
  [2,3,9,7]
]
```

```
triangle2 = [
     [3],
    [6,4],
   [3,4,7],
  [3,8,3,6]
]
```

```
triangle3 = [
     [2],
    [9,6],
   [4,5,8],
  [1,2,3,6]
]
```

but if you are feeling really clever, get it to work with these

`triangle5 = [[2], [3,4], [6,5,7], [4,1,2,3], [4,2,8,1,2],[5,4,8,7,3,2]]`

`triangle6 = [[2], [3, 4], [6, 5, 7], [4, 1, 2, 3], [4, 2, 2, 1, 2], [5, 4, 8, 4, 3, 2], [6, 5, 9, 1, 4, 3, 2]]`
