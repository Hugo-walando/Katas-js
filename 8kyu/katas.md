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

## Name : Difference of Volumes of Cuboids

```js
function findDifference(a, b) {
  let volume1 = a[0];
  let volume2 = b[0];

  for (let i = 1; i !== a.length; i++) {
    volume1 *= a[i];
  }

  for (let i = 1; i !== b.length; i++) {
    volume2 *= b[i];
  }
  return volume2 > volume1 ? volume2 - volume1 : volume1 - volume2;
}
```

## Name : I love you, a little , a lot, passionately ... not at all

```js
function howMuchILoveYou(nbPetals) {
  let arr = [
    "I love you",
    "a little",
    "a lot",
    "passionately",
    "madly",
    "not at all",
  ];
  let str = "";
  let j = "";
  console.log(nbPetals);
  arr.forEach((x, index) => {});
  for (let i = 0; i !== nbPetals; i++) {
    if (i > 5) {
      j = i % 6;
      str = arr[j];
    } else {
      str = arr[i];
    }
    console.log(str);
  }
  return str;
}
```

## Name : Reverse List Order

```js
function reverseList(list) {
  return list.reverse();
}
```

## Name : Grasshopper - Messi Goals

```js
var laLigaGoals = 43;
var championsLeagueGoals = 10;
var copaDelReyGoals = 5;

var totalGoals = laLigaGoals + championsLeagueGoals + copaDelReyGoals;
```

## Name : Welcome!

```js
function greet(language) {
  const obj = {
    english: "Welcome",
    czech: "Vitejte",
    danish: "Velkomst",
    dutch: "Welkom",
    estonian: "Tere tulemast",
    finnish: "Tervetuloa",
    flemish: "Welgekomen",
    french: "Bienvenue",
    german: "Willkommen",
    irish: "Failte",
    italian: "Benvenuto",
    latvian: "Gaidits",
    lithuanian: "Laukiamas",
    polish: "Witamy",
    spanish: "Bienvenido",
    swedish: "Valkommen",
    welsh: "Croeso",
  };
  let msg = obj[language];
  if (msg == undefined) {
    msg = "Welcome";
  }
  console.log(msg);
  return msg;
}
```

## Name : Sort and Star

```js
function twoSort(s) {
  let sorted = s.sort();
  return sorted[0].split("").join("***");
}
```

## Name : Find Multiples of a Number

```js
function findMultiples(integer, limit) {
  let arr = [];
  let count = 0;
  while (count + integer <= limit) {
    count += integer;
    arr.push(count);
  }
  return arr;
}
```

## Name : Drink about

```js
function peopleWithAgeDrink(old) {
  if (old < 14) {
    return "drink toddy";
  } else if (old < 18) {
    return "drink coke";
  } else if (old < 21) {
    return "drink beer";
  } else {
    return "drink whisky";
  }
}
```

## Name : Vowel remover

```js
function shortcut(string) {
  let arr = string.split("");
  arr = arr.filter(
    (x) => x !== "a" && x !== "e" && x !== "i" && x !== "o" && x !== "u"
  );
  return arr.join("");
}
```

## Name : Filter out the geese

```js
function gooseFilter(birds) {
  var geese = ["African", "Roman Tufted", "Toulouse", "Pilgrim", "Steinbacher"];
  return birds.filter((bird) => !geese.includes(bird));
}
```

## Name : What's the real floor?

```js
function getRealFloor(n) {
  if (n == 0) {
    return 0;
  } else if (n < 13 && n > 0) {
    n -= 1;
  } else if (n > 13) {
    n -= 2;
  }
  return n;
}
```

## Name : get character from ASCII Value

```js
function getChar(c) {
  return String.fromCharCode(c);
}
```

## Name : Name Shuffler

```js
function nameShuffler(str) {
  let arr = str.split(" ");
  let temp = arr[0];
  arr[0] = arr[1];
  arr[1] = temp;
  return arr.join(" ");
}
```

## Name : Training JS #7: if..else and ternary operator

```js
function saleHotdogs(n) {
  if (n < 5) {
    return 100 * n;
  } else if (n >= 5 && n < 10) {
    return 95 * n;
  } else {
    return 90 * n;
  }
}
```

## Name : Exclusive "or" (xor) Logical Operator

```js
function xor(a, b) {
  if (a && b) {
    return false;
  } else if (a || b) {
    return true;
  } else {
    return false;
  }
}
```

## Name : Plural

```js
function plural(n) {
  return n !== 1;
}
```

## Name : Lario and Muigi Pipe Problem

```js
function pipeFix(numbers) {
  let arr = [];
  for (let i = numbers[0]; i <= numbers[numbers.length - 1]; i++) {
    arr.push(i);
  }
  return arr;
}
```

## Name : How many lightsabers do you own?

```js
function howManyLightsabersDoYouOwn(name) {
  return name === "Zach" ? 18 : 0;
}
```

## Name : Grasshopper - Basic Function Fixer

```js
function addFive(num) {
  var total = num + 5;
  return total;
}
```

## Name : Training JS #1: create your first JS function and print "Hello World!"

```js
const helloWorld = () => {
  let str = "Hello World!";
  console.log(str);
  return str;
};
```

## Name : Multiplication table for number

```js
function multiTable(number) {
  let arr = [];
  for (let i = 1; i <= 10; i++) {
    arr.push(`${i} * ${number} = ${i * number}`);
  }
  return arr.join("\n");
}
```

## Name : Well of Ideas - Easy Version

```js
function well(x) {
  let goodCount = 0;
  x.forEach((x) => {
    if (x === "good") {
      goodCount++;
    }
  });
  if (goodCount <= 2 && goodCount >= 1) {
    return "Publish!";
  } else if (goodCount === 0) {
    return "Fail!";
  } else {
    return "I smell a series!";
  }
}
```

## Name : Super Duper Easy

```js
function problem(x) {
  if (typeof x === "number") {
    return x * 50 + 6;
  } else {
    return "Error";
  }
}
```

## Name : 5 without numbers !!

```js
function unusualFive() {
  return "foooo".length;
}
```

## Name : Regular Ball Super Ball

```js
class Ball {
  constructor(ballType = "regular") {
    this.ballType = ballType;
  }
}
```

## Name : A wolf in sheep's clothing

```js
function warnTheSheep(queue) {
  for (let i = 0; i < queue.length; i++) {
    if (queue[i] === "wolf") {
      if (queue[i + 1] === "sheep") {
        return `Oi! Sheep number ${
          queue.length - (i + 1)
        }! You are about to be eaten by a wolf!`;
      } else {
        return "Pls go away and stop eating my sheep";
      }
    }
  }
}
```

## Name : Merge two sorted arrays into one

```js
function mergeArrays(arr1, arr2) {
  for (let i = 0; i < arr1.length; i++) {
    for (let j = 0; j < arr2.length; j++) {
      if (arr1[i] === arr2[j]) {
        arr2.splice(j, 1);
      }
    }
  }
  let arr = arr1.concat(arr2);
  return arr.sort((a, b) => {
    return a - b;
  });
}
```

## Name : Remove duplicates from list

```js
function distinct(a) {
  return a.filter((el, index) => a.indexOf(el) === index);
}
```

## Name : Determine offspring sex based on genes XX and XY chromosomes

```js
function chromosomeCheck(sperm) {
  return sperm.split("").includes("Y")
    ? "Congratulations! You're going to have a son."
    : "Congratulations! You're going to have a daughter.";
}
```

## Name : The Wide-Mouthed frog!

```js
function mouthSize(animal) {
  return animal.toUpperCase() === "ALLIGATOR" ? "small" : "wide";
}
```

## Name : Add Length

```js
function addLength(str) {
  return str.split(" ").map((x) => {
    return `${x} ${x.length}`;
  });
}
```

## Name : Convert to Binary

```js
function toBinary(n) {
  return Number(n.toString(2));
}
```

## Name : Bin to Decimal

```js
function binToDec(bin) {
  return parseInt(bin, 2);
}
```

## Name : The 'if' function

```js
function _if(bool, func1, func2) {
  if (bool) {
    func1();
  } else {
    func2();
  }
}
```

## Name : Hello, Name or World!

```js
function hello(name) {
  if (name) {
    name = name.toLowerCase();
    return `Hello, ${name.charAt(0).toUpperCase()}${name.slice(1)}!`;
  } else {
    return "Hello, World!";
  }
}
```

## Name : Grasshopper - Terminal game combat function

```js
function combat(health, damage) {
  return health - damage < 0 ? 0 : health - damage;
}
```

## Name : Exclamation marks series #11: Replace all vowel to exclamation mark in the sentence

```js
function replace(s) {
  return s.replace(/[aeiouAEIOU]/g, "!");
}
```

## Name : Holiday VIII - Duty Free

```js
function dutyFree(normPrice, discount, hol) {
  let newPrice = (normPrice * discount) / 100;
  return Math.floor(hol / newPrice);
}
```

## Name : Grasshopper - Function syntax debugging

```js
function main(verb, noun) {
  return verb + noun;
}
```

## Name : Hex to Decimal

```js
function hexToDec(hexString) {
  return parseInt(hexString, 16);
}
```

## Name : Welcome to the City

```js
function sayHello(name, city, state) {
  let fullname = "";
  name.forEach((el) => {
    fullname += ` ${el}`;
  });
  return `Hello,${fullname}! Welcome to ${city}, ${state}!`;
}
```

## Name : Enumerable Magic #25 - Take the First N Elements

```js
function take(arr, n) {
  let firstItems = [];
  if (arr.length !== 0) {
    for (let i = 0; i < n; i++) {
      if (i < arr.length) {
        firstItems.push(arr[i]);
      } else {
        break;
      }
    }
  }
  return firstItems;
}
```

## Name : Find the Remainder

```js
function remainder(n, m) {
  if (m === 0 && n > 0) {
    return NaN;
  }
  return n > m ? n % m : m % n;
}
```

## Name : Surface Area and Volume of a Box

```js
function getSize(width, height, depth) {
  let arr = [];
  arr[0] = (width * height + width * depth + depth * height) * 2;
  arr[1] = width * height * depth;
  return arr;
}
```

## Name : Find the position!

```js
function position(letter) {
  let alphabet = "abcdefghijklmnopqrstuvwxyz";
  return `Position of alphabet: ${alphabet.indexOf(letter) + 1}`;
}
```

## Name : Pillars

```js
function pillars(numPill, dist, width) {
  let pillarsWidth = (numPill - 2) * width;
  let distanceTotal = dist * (numPill - 1) * 100;

  if (numPill > 1) {
    return pillarsWidth + distanceTotal;
  } else {
    return 0;
  }
}
```

## Name : Price of Mangoes

```js
function mango(quantity, price) {
  let freeMangos = Math.floor(quantity / 3);
  return (quantity - freeMangos) * price;
}
```

## Name : 101 Dalmatians - squash the bugs, not the dogs!

```js
function howManyDalmatians(number) {
  let dogs = [
    "Hardly any",
    "More than a handful!",
    "Woah that's a lot of dogs!",
    "101 DALMATIANS!!!",
  ];

  let respond =
    number <= 10
      ? dogs[0]
      : number <= 50
      ? dogs[1]
      : number >= 101
      ? dogs[3]
      : dogs[2];

  return respond;
}
```

## Name : Alan Partridge II - Apple Turnover

```js
function apple(x) {
  return Number(x) ** 2 > 1000
    ? "It's hotter than the sun!!"
    : "Help yourself to a honeycomb Yorkie for the glovebox.";
}
```

## Name : Find out whether the shape is a cube

```js
function cubeChecker(volume, side) {
  if (volume > 0 && side > 0) {
    return side ** 3 === volume ? true : false;
  }
  return false;
}
```

## Name : Training JS #2: Basic data types--Number

```js
let v1 = 50,
  v2 = 100,
  v3 = 150,
  v4 = 200,
  v5 = 2,
  v6 = 250;

function equal1() {
  let a = v1;
  let b = v1;
  return a + b;
}

//Please refer to the example above to complete the following functions
function equal2() {
  let a = v4; //set number value to a
  let b = v2; //set number value to b
  return a - b;
}

function equal3() {
  let a = v1; //set number value to a
  let b = v5; //set number value to b
  return a * b;
}

function equal4() {
  let a = v4; //set number value to a
  let b = v5; //set number value to b
  return a / b;
}

function equal5() {
  let a = v6; //set number value to a
  let b = v3; //set number value to b
  return a % b;
}
```

## Name : Printing Array elements with Comma delimiters

```js
function printArray(array) {
  console.log(`"${Array.from(array).join(",")}"`);
  return `${Array.from(array).join(",")}`;
}
```

## Name : Grasshopper - Array Mean

```js
var findAverage = function (nums) {
  let total = 0;
  nums.forEach((x) => {
    total += x;
  });
  return total / nums.length;
};
```

## Name : Reversing Words in a String

```js
function reverse(string) {
  return string.split(" ").reverse().join(" ");
}
```

## Name : Sum of differences in array

```js
function sumOfDifferences(arr) {
  let count = 0;
  if (arr.length) {
    arr.sort((a, b) => b - a);
    for (let i = 0; i < arr.length - 1; i++) {
      count += arr[i] - arr[i + 1];
    }
    return count;
  }
  return 0;
}
```

## Name : Remove First and Last Character Part Two

```js
function array(string) {
  let arr = string.split(",");
  arr.pop();
  arr.shift();
  if (arr.length > 0) {
    return arr.join(" ");
  }
  return null;
}
```

## Name : String cleaning

```js
function stringClean(s) {
  return s.replace(/\d/g, "");
}
```

## Name : Enumerable Magic - Does My List Include This?

```js
function include(arr, item) {
  return arr.includes(item);
}
```

## Name : Check same case

```js
function sameCase(a, b) {
  if (
    (a.match(/[a-z]/g) && b.match(/[a-z]/g)) ||
    (a.match(/[A-Z]/g) && b.match(/[A-Z]/g))
  ) {
    return 1;
  } else if (!a.match(/^[A-Za-z]$/) || !b.match(/^[A-Za-z]$/)) {
    return -1;
  }
  return 0;
}
```

## Name : Simple validation of a username with regex

```js
function validateUsr(username) {
  console.log(username);
  const res = /^[a-z0-9_]{4,16}$/.test(username);
  return res;
}
```

## Name : Swap Values

```js
function swapValues(args) {
  var temp = args[1];
  args[1] = args[0];
  args[0] = temp;
}
```

## Name : Sum of Multiples

```js
function sumMul(n, m) {
  let count = 0;
  if (n > 0 && m > 0) {
    for (let i = 0; i < m; i += n) {
      count += i;
    }
    return count;
  }
  return "INVALID";
}
```

## Name : Training JS #5: Basic data types--Object

```js
function animal(obj) {
  let animal = {
    name: obj.name,
    legs: obj.legs,
    color: obj.color,
  };
  return `This ${animal.color} ${animal.name} has ${animal.legs} legs.`;
}
```

## Name : Multiple of index

```js
function multipleOfIndex(array) {
  let newArray = [];
  for (let i = 0; i < array.length; i++) {
    console.log(array[i], i);
    console.log(array[i] % i);
    if (array[i] % i === 0 || array[i] === 0) {
      newArray.push(array[i]);
    }
    console.log(newArray);
  }
  return newArray;
}
```

## Name : Sleigh Authentication

```js
function Sleigh() {}

Sleigh.prototype.authenticate = function (name, password) {
  return name === "Santa Claus" && password === "Ho Ho Ho!" ? true : false;
};
```

## Name : Fundamentals: Return

```js
function add(a, b) {
  return a + b;
}

function divide(a, b) {
  return a / b;
}

function multiply(a, b) {
  return a * b;
}

function mod(a, b) {
  return a % b;
}

function exponent(a, b) {
  return a ** b;
}

function subt(a, b) {
  return a - b;
}
```

## Name : Take the Derivative

```js
function derive(coefficient, exponent) {
  return `${coefficient * exponent}x^${exponent - 1}`;
}
```

## Name : Find Nearest square number

```js
function nearestSq(n) {
  // Calculer la racine carrée de n
  const sqrt = Math.sqrt(n);

  // Trouver les entiers les plus proches de la racine carrée
  const lower = Math.floor(sqrt);
  const upper = Math.ceil(sqrt);

  // Calculer les carrés de ces entiers
  const lowerSq = lower * lower;
  const upperSq = upper * upper;

  // Comparer les carrés avec n et retourner le plus proche
  if (Math.abs(n - lowerSq) <= Math.abs(n - upperSq)) {
    return lowerSq;
  } else {
    return upperSq;
  }
}
```

## Name : Kata Example Twist

```js
let websites = [];
for (let i = 0; i < 1000; i++) {
  websites.push("codewars");
}
```

## Name : L1: Bartender, drinks!

```js
function getDrinkByProfession(param) {
  param = param.toLowerCase();
  switch (param) {
    case "jabroni":
      return "Patron Tequila";
    case "school counselor":
      return "Anything with Alcohol";
    case "programmer":
      return "Hipster Craft Beer";
    case "bike gang member":
      return "Moonshine";
    case "politician":
      return "Your tax dollars";
    case "rapper":
      return "Cristal";
    default:
      return "Beer";
  }
}
```

## Name : How old will I be in 2099?

```js
function calculateAge(a, b) {
  if (a - b === 0) {
    return "You were born this very year!";
  }
  if (a > b) {
    if (a - b === 1) {
      return `You will be born in ${1} year.`;
    }
    return `You will be born in ${a - b} years.`;
  } else {
    if (b - a === 1) {
      return `You are ${1} year old.`;
    }
    return `You are ${b - a} years old.`;
  }
}
```

## Name : Return the day

```js
function whatday(num) {
  if (num >= 1 && num <= 7) {
    switch (num) {
      case 1:
        return "Sunday";
      case 2:
        return "Monday";
      case 3:
        return "Tuesday";
      case 4:
        return "Wednesday";
      case 5:
        return "Thursday";
      case 6:
        return "Friday";
      case 7:
        return "Saturday";
    }
  }
  return "Wrong, please enter a number between 1 and 7";
}
```

## Name : Basic Training: Add item to an Array

```js
websites.push("codewars");
```

## Name : Training JS #4: Basic data types--Array

```js
function getLength(arr) {
  return arr.length;
}
function getFirst(arr) {
  return arr[0];
}
function getLast(arr) {
  return arr[arr.length - 1];
}
function pushElement(arr) {
  var el = 1;
  arr.push(el);
  return arr;
}
function popElement(arr) {
  arr.pop();
  return arr;
}
```

## Name : Regex count lowercase letters

```js
function lowercaseCount(str) {
  let regex = /[a-z]/g;
  let arr = [];
  arr = str.match(regex);
  if (arr !== null && arr.length > 0) {
    return arr.length;
  }
  return 0;
}
```

## Name : Grasshopper - Combine strings

```js
const combineNames = (first, last) => {
  return `${first} ${last}`;
};
```

## Name : USD => CNY

```js
function usdcny(usd) {
  return `${(Math.round(usd * 6.75 * 100) / 100).toFixed(2)} Chinese Yuan`;
}
```

## Name : Formatting decimal places #0

```js
function twoDecimalPlaces(n) {
  return Math.round(n * 100) / 100;
}
```

## Name : Area of a Square

```js
function squareArea(A) {
  return Number(Math.pow((A * 4) / (Math.PI * 2), 2).toFixed(2));
}
```

## Name : OOP: Object Oriented Piracy

```js
class Ship {
  constructor(draft, crew) {
    this.draft = draft;
    this.crew = crew;
  }

  isWorthIt() {
    return this.draft - this.crew * 1.5 > 20 ? true : false;
  }
}
```

## Name : Multiply the number

```js
function multiply(number) {
  let numStr = Math.abs(number).toString();
  let expo = numStr.length;
  return number * 5 ** expo;
}
```

## Name : How many stairs will Suzuki climb in 20 years?

```js
function stairsIn20(s) {
  let estimate = 0;
  for (let i = 0; i < s.length; i++) {
    for (let j = 0; j < s[i].length; j++) {
      estimate += s[i][j];
    }
  }
  return estimate * 20;
}
```

## Name : Color Ghost

```js
class Ghost {
  constructor() {
    const colors = ["white", "yellow", "purple", "red"];
    this.color = colors[Math.floor(Math.random() * colors.length)];
  }
}
```

## Name : Name on billboard

```js
function billboard(name, price = 30) {
  let total = 0;
  name.split("").forEach((x) => {
    total += price;
  });
  return total;
}
```

## Name : Define a card suit

```js
function defineSuit(card) {
  let arr = card.split("");
  for (let x of arr) {
    console.log(x);
    switch (x) {
      case "♣":
        return "clubs";
      case "♦":
        return "diamonds";
      case "♥":
        return "hearts";
      case "♠":
        return "spades";
    }
  }
}
```

## Name : Basic subclasses - Adam and Eve

```js
class God {
  static create() {
    const adam = new Man("Adam");
    const eve = new Woman("Eve");
    return [adam, eve];
  }
}

class Human {
  constructor(name) {
    this.name = name;
  }
}

class Man extends Human {
  constructor(name) {
    super(name);
  }
}

class Woman extends Human {
  constructor(name) {
    super(name);
  }
}
```

## Name : Type of sum

```js
function typeOfSum(a, b) {
  return typeof (a + b);
}
```

## Name : Do you speak "English"?

```js
function spEng(sentence) {
  return sentence.toLowerCase().includes("english");
}
```

## Name : Holiday VI - Shark Pontoon

```js
function shark(pontoonDistance, sharkDistance, youSpeed, sharkSpeed, dolphin) {
  return pontoonDistance / youSpeed <
    sharkDistance / (dolphin ? sharkSpeed / 2 : sharkSpeed)
    ? "Alive!"
    : "Shark Bait!";
}
```

## Name : Remove the time

```js
function shortenToDate(longDate) {
  return longDate.split(",").shift();
}
```

## Name : No Loops 2 - You only need one

```js
function check(a, x) {
  return a.includes(x);
}
```

## Name : Fix your code before the garden dies

```js
function rainAmount(mm) {
  if (mm < 40) {
    return `You need to give your plant ${40 - mm}mm of water`;
  } else {
    return "Your plant has had more than enough water for today!";
  }
}
```

## Name : Training JS #8: Conditional statement--switch

```js
function howManydays(month) {
  var days;
  switch (month) {
    case 4:
    case 6:
    case 9:
    case 11:
      days = 30;
      break;
    case 2:
      days = 28;
      break;
    default:
      days = 31;
  }
  return days;
}
```

## Name : Exclamation marks series #2: Remove all exclamation marks from the end of sentence

```js
function remove(string) {
  let arr = string.split("");
  for (let i = arr.length - 1; i > 0; i--) {
    if (arr[i] === "!") {
      arr.splice(i, 1);
    } else {
      return arr.join("");
    }
  }
}
```

## Name : Classic Hello World

```js
class Solution {
  static main() {
    console.log("Hello World!");
  }
}
```

## Name : Classy Classes

```js
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  get info() {
    return `${this.name}s age is ${this.age}`;
  }
}
```

## Name : Regexp Basics - is it a digit?

```js
String.prototype.digit = function () {
  return /^[0-9]{1}$/g.test(this);
};
```

## Name :

Contamination #1 -String-

```js
function contamination(text, char) {
  let arr = text.split("");
  for (let i = 0; i < arr.length; i++) {
    arr[i] = char;
  }
  return arr.join("");
}
```

## Name : Pythagorean Triple

```js
function isPythagoreanTriple(integers) {
  integers.sort((a, b) => a - b);
  return integers[0] ** 2 + integers[1] ** 2 === integers[2] ** 2;
}
```

## Name : Is it a number?

```js
function isDigit(s) {
  let num = Math.abs(s);
  console.log(NaN);
  console.log(num == NaN);
  return typeof num === "number" && !isNaN(num) && s.trim() !== "";
}
```

## Name : Leonardo Dicaprio and Oscars

```js
function leo(oscar) {
  if (oscar === 88) {
    return "Leo finally won the oscar! Leo is happy";
  } else if (oscar === 86) {
    return "Not even for Wolf of wallstreet?!";
  } else if (oscar < 88) {
    return "When will you give Leo an Oscar?";
  } else {
    return "Leo got one already!";
  }
}
```

## Name : Training JS #6: Basic data types--Boolean and conditional statements if..else

```js
function trueOrFalse(val) {
  return val ? "true" : "false";
}
```

## Name : Exclamation marks series #6: Remove n exclamation marks in the sentence from left to right

```js
function remove(s, n) {
  let count = 0;
  let arr = s.split("");

  for (let i = 0; i < arr.length; i++) {
    if (count < n && arr[i] === "!") {
      arr.splice(i, 1);
      count++;
      i--;
    }
  }

  return arr.join("");
}
```

## Name : get ascii value of character

```js
function getASCII(c) {
  return c.charCodeAt(0);
}
```

## Name : Quadrants

```js
function quadrant(x, y) {
  if (x > 0 && y > 0) {
    return 1;
  } else if (x > 0 && y < 0) {
    return 4;
  } else if (x < 0 && y > 0) {
    return 2;
  } else {
    return 3;
  }
}
```

## Name : Smallest unused ID

```js
function nextId(ids) {
  let arr = ids.sort((a, b) => a - b);
  console.log(arr);
  for (let i = 0; i < arr.length; i++) {
    if (arr[0] !== 0) return 0;
    if (arr[i + 1] !== arr[i] + 1 && arr[i] !== arr[i + 1]) {
      return arr[i] + 1;
    }
  }
  return arr.lenght + 1;
}
```

## Name : Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string

```js
function remove(string) {
  return string.replaceAll("!", "") + "!";
}
```

## Name : A Strange Trip to the Market

```js
function isLockNessMonster(s) {
  return s.includes("tree fiddy") ||
    s.includes("3.50") ||
    s.includes("three fifty")
    ? true
    : false;
}
```

## Name : Compare within margin

```js
function closeCompare(a, b, margin = 0) {
  if (a > b) {
    if (a - b <= margin) {
      return 0;
    }
    return 1;
  } else {
    if (b - a <= margin) {
      return 0;
    }
    return -1;
  }
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
