// Assisgnment 1

function numbers(a, b) {
  if (a == 50 || b == 50 || a + b == 50) {
    return true;
  }
}
console.log(numbers(20, 50));

// Assignment 2

function check(x) {
  return Math.sign(x);
}
console.log(check(5));
console.log(check(-2));

// Assignment 3
const str = "python";

console.log(str.substring(0, 2));

function newString(x) {
  if (x === null || x === undefined || x.substring(0, 2) === "py") {
    return x;
  } else {
    return "py" + x;
  }
}
console.log(newString("py"));
console.log(newString("x"));

// Assignment 4

function maximumValue(a, b, c) {
  value = 0;
  if (a > b) {
    value = a;
  } else {
    value = b;
  }
  if (c > value) {
    value = c;
  }
  return value;
}

console.log(maximumValue(10, 15, 9));

// Assignment 5

function value(a, b) {
  if (a != b) {
    fNum = Math.abs(a - 100);
    sNum = Math.abs(b - 100);
    if (fNum < sNum) {
      return a;
    }
    if (sNum < fNum) {
      return b;
    } else {
      return 0;
    }
  }
}
console.log(value(85, 75));

// Assignment 6

function threeNumbers(x, y, z) {
  if (x == y && y == z) {
    return 30;
  } else if (x == y || y == z || z == x) {
    return 40;
  }
  return 20;
}

console.log(threeNumbers(10, 10, 20));
console.log(threeNumbers(10, 5, 20));

// Assignment 7

function reverse(string) {
  return string.split("").reverse().join("");
}
console.log(reverse("letusgobacktothetime"));

// Asignment 8

function count(string) {
  return string.replace(/[^aeiou]/g, "").length;
}
console.log(count("iloveyou"));

// Assignment 9

let str = "Summer After High School When We First Met";

const split_string = str.split("-");

console.log(split_string);

// Assignment 10

const person = {
  name: "Garfield",
  age: 15,
  species: "cat",
  about: function () {
    console.log(
      `${this.name} who is a ${this.species} is ${this.age} years old`
    );
  },
};
console.log(person.about());
