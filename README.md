# my-dash

This is my attempt at recreating the functionality of [lodash](https://github.com/lodash/lodash/). It's just an exercise for me to practice my JavaScript skills, but feel free to fork it or send a pull request.

#####Methods Created:

######chunk

 - Takes two arguments, an array and a number. The array is divided into sub arrays with the length of the number. If the array is not divisible by the number the remaining values are grouped into the last array. So:

```JavaScript
chunk([1, 2, 3, 4, 5, 6], 2)
```

returns ```JavaScript
[[1, 2], [3, 4], [5, 6]]```

and

```JavaScript
chunk([1, 2, 3, 4, 5, 6, 7], 3)```

returns ```JavaScript
[[1, 2, 3], [4, 5, 6], [7]]```

######compact

- Takes one argument that is an array and returns a new array with the falsey values removed. So:

```JavaScript
compact([1, 0, false, 'eggplant'])
```

returns ```JavaScript
[1, 'eggplant']```

