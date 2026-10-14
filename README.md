# Javascript.bilal


let a = 10, b = 5;

console.log("Addition:", a + b);
console.log("Subtraction:", a - b);
console.log("Multiplication:", a * b);
console.log("Division:", a / b);


let a = 10, b = 5;

console.log(a > b);
console.log(a < b);
console.log(a == b);
console.log(a != b);
console.log(a >= b);
console.log(a <= b);


let a = 10, b = 5;

console.log(a > 5 && b < 10);
console.log(a > 15 || b < 10);
console.log(!(a > b));



let n = 10;

if (n > 0)
    console.log("Positive number");
else
    console.log("Not positive");



let n = 7;

if (n % 2 == 0)
    console.log("Even");
else
    console.log("Odd");


let age = 20;

if (age >= 18)
    console.log("Eligible to vote");
else
    console.log("Not eligible to vote");


let n = -5;

if (n > 0)
    console.log("Positive");
else if (n < 0)
    console.log("Negative");
else
    console.log("Zero");


let marks = 85;

if (marks >= 90)
    console.log("Grade A+");
else if (marks >= 80)
    console.log("Grade A");
else if (marks >= 70)
    console.log("Grade B");
else if (marks >= 60)
    console.log("Grade C");
else if (marks >= 40)
    console.log("Grade D");
else
    console.log("Fail");



let a = 10, b = 20;

if (a > b)
    console.log("Largest:", a);
else if (b > a)
    console.log("Largest:", b);
else
    console.log("Both are equal");



let year = 2024;

if ((year % 4 == 0 && year % 100 != 0) ||
    year % 400 == 0)
    console.log("Leap year");
else
    console.log("Not a leap year");


let count = 0;

for (let i = 1; i <= 100; i++) {
    if (i % 3 == 0)
        count++;
}

console.log("Count:", count);



let a = 10, b = 25, c = 15;

if (a >= b && a >= c)
    console.log("Largest:", a);
else if (b >= a && b >= c)
    console.log("Largest:", b);
else
    console.log("Largest:", c);



let n = 15;

if (n % 3 == 0 && n % 5 == 0)
    console.log("Divisible by both 3 and 5");
else
    console.log("Not divisible by both");
