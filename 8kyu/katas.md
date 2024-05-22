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

## Name : Returning Strings

```js
function greet(name) {
  return `Hello, ${name} how are you doing today?`;
}
```

## Name : Convert a Boolean to a String

```js
function booleanToString(b) {
  return b + "";
}
```

## Name : Basic Mathematical Operations

```js
function basicOp(operation, value1, value2) {
  switch (operation) {
    case "+":
      return value1 + value2;
    case "-":
      return value1 - value2;
    case "*":
      return value1 * value2;
    case "/":
      return value1 / value2;
  }
}
```

## Name : Keep Hydrated!

```js
function litres(time) {
  return Math.floor(time * 0.5);
}
```

## Name : Century From Year

```js
function century(year) {
  let firstDigit = (year - (year - Math.floor(year / 100) * 100)) / 100;
  if (year - Math.floor(year / 100) * 100 === 0) {
    return firstDigit;
  } else {
    return firstDigit === 1 ? firstDigit : firstDigit + 1;
  }
}
```

## Name : Beginner - Lost Without a Map

```js
function maps(x) {
  return x.map((num) => {
    return num * 2;
  });
}
```

## Name : Convert number to reversed array of digits

```js
function digitize(n) {
  let arr = Array.from(String(n)).reverse();
  return arr.map((el) => {
    return +el;
  });
}
```

## Name : Opposites Attract

```js
function lovefunc(flower1, flower2) {
  if (flower1 % 2 !== 0 && flower2 % 2 !== 0) {
    return false;
  } else if (flower1 % 2 === 0 && flower2 % 2 === 0) {
    return false;
  } else {
    return true;
  }
}
```

## Name : Beginner Series #1 School Paperwork

```js
function paperwork(n, m) {
  if (n < 0 || m < 0) {
    return 0;
  }
  return n * m;
}
```

## Name : Beginner Series #2 Clock

```js
function past(h, m, s) {
  let hoursInMilliseconds = h * 3600000;
  let minutesInMilliseconds = m * 60000;
  let secondsInMilliseconds = s * 1000;
  let result =
    hoursInMilliseconds + minutesInMilliseconds + secondsInMilliseconds;
  return result;
}
```

## Name : Simple multiplication

```js
function simpleMultiplication(number) {
  if (number % 2) return number * 9;
  return number * 8;
}
```

## Name : Abbreviate a Two Word Name

```js
function abbrevName(name) {
  let arr = [];
  name.split(" ").forEach((el) => {
    arr.push(el[0]);
  });
  return arr.join(".").toUpperCase();
}
```

## Name : Are You Playing Banjo?

```js
function areYouPlayingBanjo(name) {
  if (name[0] === "r" || name[0] === "R") {
    return name + " plays banjo";
  }
  return name + " does not play banjo";
}
```

## Name : A Needle in the Haystack

```js
function findNeedle(haystack) {
  let message = "";
  haystack.forEach((el, index) => {
    if (el === "needle") {
      message = `found the needle at position ${index}`;
    }
  });
  return message;
}
```

## Name : Invert values

```js
function invert(array) {
  return array.map((num) => {
    return -num;
  });
}
```

## Name : Calculate average

```js
function findAverage(array) {
  let sum = 0;
  if (array.length > 0) {
    array.forEach((el) => {
      sum += el;
    });
    return sum / array.length;
  }
  return 0;
}
```

## Name : Is he gonna survive?

```js
function hero(bullets, dragons) {
  return bullets / 2 >= dragons ? true : false;
}
```

## Name : How good are you really?

```js
function betterThanAverage(classPoints, yourPoints) {
  let sum = 0;
  let average = 0;
  classPoints.forEach((num) => {
    sum += num;
    average = sum / classPoints.length;
  });
  return average < yourPoints ? true : false;
}
```

## Name : Count of positives / sum of negatives

```js
function countPositivesSumNegatives(input) {
  let positiveCount = 0;
  let negativeSum = 0;
  let result = [];
  if (Array.isArray(input) && input.length) {
    input.forEach((num) => {
      if (num > 0) {
        positiveCount++;
      } else {
        negativeSum += num;
      }
    });
    result.push(positiveCount, negativeSum);
  }
  return result;
}
```

## Name : Calculate BMI

```js
function bmi(weight, height) {
  let bmi = weight / height ** 2;
  if (bmi <= 18.5) {
    return "Underweight";
  } else if (bmi <= 25) {
    return "Normal";
  } else if (bmi <= 30) {
    return "Overweight";
  } else {
    return "Obese";
  }
}
```

## Name : Find Maximum and Minimum Values of a List

```js
var min = function (list) {
  return Math.min(...list);
};

var max = function (list) {
  return Math.max(...list);
};
```

## Name : Fake Binary

```js
function fakeBin(x) {
  return Array.from(x)
    .map((num) => {
      if (num >= 5) {
        return (num = 1);
      } else {
        return (num = 0);
      }
    })
    .join("");
}
```

## Name : You only need one - Beginner

```js
function check(a, x) {
  return a.includes(x);
}
```

## Name : DNA to RNA Conversion

```js
function DNAtoRNA(dna) {
  let rna = Array.from(dna).map((el) => {
    if (el === "T") {
      return (el = "U");
    }
    return el;
  });
  return rna.join("");
}
```

## Name : Will you make it?

```js
const zeroFuel = (distanceToPump, mpg, fuelLeft) => {
  return distanceToPump <= mpg * fuelLeft ? true : false;
};
```

## Name : Convert a string to an array

```js
function stringToArray(string) {
  return string.split(" ");
}
```

## Name : Reversed sequence

```js
const reverseSeq = (n) => {
  let arr = [];
  if (n > 0) {
    for (let i = n; i !== 0; i--) {
      arr.push(i);
    }
  }
  return arr;
};
```

## Name : Count by X

```js
function countBy(x, n) {
  let arr = [];
  let sum = 0;
  for (let i = 0; i !== n; i++) {
    sum += x;
    arr.push(sum);
  }
  return arr;
}
```

## Name : Rock Paper Scissors!

```js
const rps = (p1, p2) => {
  if (
    (p1 === "scissors" && p2 === "scissors") ||
    (p1 === "paper" && p2 === "paper") ||
    (p1 === "rock" && p2 === "rock")
  ) {
    return `Draw!`;
  } else if (
    (p1 === "scissors" && p2 === "paper") ||
    (p1 === "paper" && p2 === "rock") ||
    (p1 === "rock" && p2 === "scissors")
  ) {
    return `Player 1 won!`;
  } else {
    return `Player 2 won!`;
  }
};
```

## Name : If you can't sleep, just count sheep!!

```js
var countSheep = function (num) {
  let result = "";
  if (num > 0) {
    for (let i = 0; i !== num; i++) {
      result += `${i + 1} sheep...`;
    }
  }
  return result;
};
```

## Name : Grasshopper - Personalized Message

```js
function greet(name, owner) {
  if (name === owner) {
    return "Hello boss";
  } else {
    return "Hello guest";
  }
}
```

## Name : Quarter of the year

```js
const quarterOf = (month) => {
  if (month <= 3) {
    return 1;
  } else if (month <= 6) {
    return 2;
  } else if (month <= 9) {
    return 3;
  } else {
    return 4;
  }
};
```

## Name : Grasshopper - Grade book

```js
function getGrade(s1, s2, s3) {
  let average = (s1 + s2 + s3) / 3;
  if (average < 60) {
    return "F";
  } else if (average < 70) {
    return "D";
  } else if (average < 80) {
    return "C";
  } else if (average < 90) {
    return "B";
  } else if (average <= 100) {
    return "A";
  }
}
```

## Name : Transportation on vacation

```js
function rentalCarCost(d) {
  if (d < 3) {
    return 40 * d;
  } else if (d < 7) {
    return 40 * d - 20;
  } else {
    return 40 * d - 50;
  }
}
```

## Name : Remove exclamation marks

```js
function removeExclamationMarks(s) {
  return s.replaceAll("!", "");
}
```

## Name : Total amount of points

```js
function points(games) {
  let points = 0;
  games.forEach((score) => {
    let arr = score.split(":");
    if (arr[0] === arr[1]) {
      points++;
    } else if (arr[0] > arr[1]) {
      points += 3;
    }
  });
  return points;
}
```

## Name : Volume of a Cuboid

```js
class Kata {
  static getVolumeOfCuboid(length, width, height) {
    return length * width * height;
  }
}
```

## Name : Third Angle of a Triangle

```js
function otherAngle(a, b) {
  return 180 - (a + b);
}
```

## Name : Area or Perimeter

```js
const areaOrPerimeter = function (l, w) {
  if (l === w) {
    return l * w;
  } else {
    return (l + w) * 2;
  }
};
```

## Name : Thinkful - Logic Drills: Traffic light

```js
function updateLight(current) {
  if (current === "green") {
    return "yellow";
  } else if (current === "yellow") {
    return "red";
  }
  return "green";
}
```

## Name : L1: Set Alarm

```js
function setAlarm(employed, vacation) {
  if (employed && !vacation) {
    return true;
  }
  return false;
}
```

## Name : Sum without highest and lowest number

```js
function sumArray(array) {
  let sum = 0;
  let minFound = false;
  let maxFound = false;
  if (array) {
    const newArray = array.filter((item) => {
      if (item === Math.min(...array) && !minFound) {
        minFound = true;
        return false; // Ne pas inclure la première occurrence de `min`
      }
      if (item === Math.max(...array) && !maxFound) {
        maxFound = true;
        return false; // Ne pas inclure la première occurrence de `min`
      }
      return true;
      return item !== Math.min(...array) && item !== Math.max(...array);
    });
    console.log(newArray);
    sum = newArray.reduce((a, b) => a + b, 0);
  }
  return sum;
}
```

## Name : Sum Mixed Array

```js
function sumMix(x) {
  return x.reduce((a, b) => +a + +b, 0);
}
```

## Name : Grasshopper - Messi goals function

```js
function goals(laLigaGoals, copaDelReyGoals, championsLeagueGoals) {
  return laLigaGoals + copaDelReyGoals + championsLeagueGoals;
}
```

## Name : Double Char

```js
function doubleChar(str) {
  let arr = str.split("");
  let newArray = [];
  arr.forEach((char) => {
    newArray.push(char);
    newArray.push(char);
  });
  return newArray.join("");
}
```

## Name : The Feast of Many Beasts

```js
function feast(beast, dish) {
  if (beast[0] === dish[0] && beast.slice(-1) === dish.slice(-1)) {
    return true;
  } else {
    return false;
  }
}
```

## Name : Array plus array

```js
function arrayPlusArray(arr1, arr2) {
  return arr1.reduce((a, b) => a + b, 0) + arr2.reduce((a, b) => a + b, 0);
}
```

## Name : Parse nice int from char problem

```js
function getAge(inputString) {
  return +inputString[0];
}
```

## Name : Grasshopper - Check for factor

```js
function checkForFactor(base, factor) {
  return base % factor === 0;
}
```

## Name : Switch it Up!

```js
function switchItUp(number) {
  switch (number) {
    case 0:
      return "Zero";
    case 1:
      return "One";
    case 2:
      return "Two";
    case 3:
      return "Three";
    case 4:
      return "Four";
    case 5:
      return "Five";
    case 6:
      return "Six";
    case 7:
      return "Seven";
    case 8:
      return "Eight";
    case 9:
      return "Nine";
  }
}
```

## Name : Function 2 - squaring an argument

```js
const square = (x) => {
  return x ** 2;
};
```

## Name : Keep up the hoop

```js
function hoopCount(n) {
  return n >= 10
    ? "Great, now move on to tricks"
    : "Keep at it until you get it";
}
```

## Name : Twice as old

```js
function twiceAsOld(dadYearsOld, sonYearsOld) {
  let years = 0;
  if (dadYearsOld > sonYearsOld * 2) {
    while (sonYearsOld * 2 !== dadYearsOld) {
      dadYearsOld++;
      sonYearsOld++;
      years++;
    }
  } else {
    while (sonYearsOld * 2 !== dadYearsOld) {
      dadYearsOld--;
      sonYearsOld--;
      years++;
    }
  }
  return years;
}
```

## Name : Removing Elements

```js
function removeEveryOther(arr) {
  return arr.filter((x, index) => {
    return index % 2 === 0;
  });
}
```

## Name : Count the Monkeys!

```js
function monkeyCount(n) {
  let arr = [];
  for (let i = 1; i !== n + 1; i++) {
    arr.push(i);
  }
  return arr;
}
```

## Name : Will there be enough space?

```js
function enough(cap, on, wait) {
  if (cap < on + wait) {
    return on + wait - cap;
  } else {
    return 0;
  }
}
```

## Name : All Star Code Challenge #18

```js
function strCount(str, letter) {
  let arr = str.split("");
  let count = 0;
  arr.forEach((x) => {
    if (x == letter) {
      count++;
    }
  });
  return count;
}
```

## Name : Grasshopper - Terminal game move function

```js
function move(position, roll) {
  return position + roll * 2;
}
```

## Name : What is between?

```js
function between(a, b) {
  let arr = [];
  for (let i = a; i <= b; i++) {
    arr.push(i);
  }
  return arr;
}
```

## Name : Grasshopper - Debug sayHello

```js
function sayHello(name) {
  return `Hello, ${name}`;
}
```

## Name : Find the first non-consecutive number

```js
function firstNonConsecutive(arr) {
  let prevValue = arr[0];
  for (let i = 1; i !== arr.length; i++) {
    if (arr[i] !== prevValue + 1) {
      return arr[i];
    }
    prevValue++;
  }
  return null;
}
```

## Name : Is it even?

```js
function testEven(n) {
  return n % 2 === 0;
}
```

## Name : Is the string uppercase?

```js
String.prototype.isUpperCase = function () {
  let a = this.split("");
  console.log(a);
  for (const x of a) {
    console.log(x);
    if (x !== x.toUpperCase()) {
      return false;
    }
  }
  return true;
};
```

## Name : Cat years, Dog years

```js
var humanYearsCatYearsDogYears = function (humanYears) {
  let catYears = 0;
  let dogYears = 0;

  for (let i = 0; i !== humanYears + 1; i++) {
    if (i == 1) {
      catYears += 15;
      dogYears += 15;
    }
    if (i == 2) {
      catYears += 9;
      dogYears += 9;
    }
    if (i > 2) {
      catYears += 4;
      dogYears += 5;
    }
  }
  return [humanYears, catYears, dogYears];
};
```

## Name : altERnaTIng cAsE <=> ALTerNAtiNG CaSe

```js
String.prototype.toAlternatingCase = function () {
  let arr = this.split("");
  arr = arr.map((x) => {
    return x == x.toUpperCase() ? x.toLowerCase() : x.toUpperCase();
  });
  return arr.join("");
};
```

## Name : Correct the mistakes of the character recognition software

```js
function correct(string) {
  let arr = string.split("");
  arr = arr.map((x) => {
    if (x === "5") {
      return (x = "S");
    } else if (x === "1") {
      return (x = "I");
    } else if (x === "0") {
      return (x = "O");
    }
    return x;
  });
  return arr.join("");
}
```

## Name : Is it a palindrome?

```js
function isPalindrome(x) {
  let arr = x.split("");
  if (x == "") {
    return true;
  }
  for (const [index, value] of arr.entries()) {
    if (value.toUpperCase() != arr[arr.length - index - 1].toUpperCase()) {
      return false;
    }
    return true;
  }
}
```

## Name : Student's Final Grade

```js
function finalGrade(exam, projects) {
  if (exam > 90 || projects > 10) {
    return 100;
  } else if (exam > 75 && projects >= 5) {
    return 90;
  } else if (exam > 50 && projects >= 2) {
    return 75;
  } else {
    return 0;
  }
}
```

## Name : Expressions Matter

```js
function expressionMatter(a, b, c) {
  let A = a * b * c;
  let B = a + b * c;
  let C = a * b + c;
  let D = a + b + c;
  let E = a * b * c;
  let F = a * (b * c);
  let G = (a + b) * c;
  let H = a * (b + c);
  return Math.max(A, B, C, D, E, F, G, H);
}
```

## Name : Sum The Strings

```js
function sumStr(a, b) {
  return `${+a + +b}`;
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
