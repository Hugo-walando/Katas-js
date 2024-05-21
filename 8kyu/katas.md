## Name :

```js

```

## Name : Reverse string

```js
function solution(str) {
  return str.split("").reverse().join("");
}
```

## Name : Opposite number

```js
function opposite(number) {
  return -number;
}
```

## Name : Return Negative

```js
return num < 0 ? num : -num;
```

## Name : Convert boolean values to strings 'Yes' or 'No'.

```js
function boolToWord(bool) {
  return bool ? "Yes" : "No";
}
```

## Name : Sum of positive

```js
function positiveSum(arr) {
  let sum = 0;
  arr.forEach((el) => {
    if (el > 0) {
      sum += el;
    }
  });
  return sum;
}
```

## Name : String repeat

```js
function repeatStr(n, s) {
  let str = "";
  for (let i = 0; i < n; i++) {
    str += s;
  }
  return str;
}
```

## Name : Remove First and Last Character

```js
function removeChar(str) {
  let arr = str.split("");
  arr.pop();
  arr.shift();
  return arr.join("");
}
```

## Name : Square(n) Sum

```js
function squareSum(numbers) {
  let sum = 0;
  numbers.forEach((num) => {
    let squareNum = num ** 2;
    sum += squareNum;
  });
  return sum;
}
```

## Name : Find the smallest integer in the array

```js
class SmallestIntegerFinder {
  findSmallestInt(args) {
    let small = args[0];
    args.forEach((num) => {
      if (num < small) {
        small = num;
      }
    });
    return small;
  }
}
```

## Name : Grasshopper - Summation

```js
var summation = function (num) {
  let sum = 0;
  for (let i = num; i !== 0; i--) {
    sum += i;
  }
  return sum;
};
```

## Name : Convert a String to a Number!

```js
const stringToNumber = function (str) {
  return +str;
};
```

## Name : Function 1 - hello world

```js
const greet = () => {
  return "hello world!";
};
```

## Name : Counting sheep...

```js
function countSheeps(sheep) {
  let sum = 0;
  sheep.forEach((s) => {
    if (s) sum += 1;
  });
  return sum;
}
```

## Name : Remove String Spaces

```js
function noSpace(x) {
  return x.split(" ").join("");
}
```

## Name : You Can't Code Under Pressure #1

```js
function doubleInteger(i) {
  i *= 2;
  return i;
}
```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```

## Name :

```js

```
