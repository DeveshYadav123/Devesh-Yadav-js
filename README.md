# Devesh-Yadav-js


 // 1. Arithmetic Operations on Two Numbers
let a = 10, b = 5;

console.log("Addition:", a + b);
console.log("Subtraction:", a - b);
console.log("Multiplication:", a * b);
console.log("Division:", a / b);


// 2. Comparison Operators
let x = 10, y = 5;

console.log(x > y);
console.log(x < y);
console.log(x == y);
console.log(x != y);
console.log(x >= y);
console.log(x <= y);


// 3. Logical Operators (&&, ||, !)
let p = 10, q = 5;

console.log(p > 5 && q < 10);
console.log(p > 15 || q < 10);
console.log(!(p > q));


// 4. Check Whether a Number is Positive
let n = 10;

if (n > 0)
    console.log("Positive number");
else
    console.log("Not positive");


// 5. Check Whether a Number is Even or Odd
let num = 7;

if (num % 2 == 0)
    console.log("Even");
else
    console.log("Odd");


// 6. Check Voting Eligibility
let age = 20;

if (age >= 18)
    console.log("Eligible to vote");
else
    console.log("Not eligible to vote");


// 7. Check Positive, Negative, or Zero
let number = -5;

if (number > 0)
    console.log("Positive");
else if (number < 0)
    console.log("Negative");
else
    console.log("Zero");


// 8. Calculate Grades Based on Marks
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


// 9. Find the Largest of Two Numbers
let first = 10, second = 20;

if (first > second)
    console.log("Largest:", first);
else if (second > first)
    console.log("Largest:", second);
else
    console.log("Both are equal");


// 10. Check Whether a Year is a Leap Year
let year = 2024;

if ((year % 4 == 0 && year % 100 != 0) ||
    year % 400 == 0)
    console.log("Leap year");
else
    console.log("Not a leap year");


// 11. Print Numbers from 1 to 10
for (let i = 1; i <= 10; i++) {
    console.log(i);
}


// 12. Multiplication Table of a Given Number
let table = 5;

for (let i = 1; i <= 10; i++) {
    console.log(table + " x " + i + " = " + (table * i));
}


// 13. Sum of the First N Natural Numbers
let limit = 10, sum = 0;

for (let i = 1; i <= limit; i++) {
    sum += i;
}

console.log("Sum:", sum);


// 14. Print Even Numbers Between 1 and 50
for (let i = 2; i <= 50; i += 2) {
    console.log(i);
}


// 15. Count Numbers Divisible by 3 Between 1 and 100
let count = 0;

for (let i = 1; i <= 100; i++) {
    if (i % 3 == 0)
        count++;
}

console.log("Count:", count);


// 16. Find the Largest of Three Numbers
let firstNum = 10, secondNum = 25, thirdNum = 15;

if (firstNum >= secondNum && firstNum >= thirdNum)
    console.log("Largest:", firstNum);
else if (secondNum >= firstNum && secondNum >= thirdNum)
    console.log("Largest:", secondNum);
else
    console.log("Largest:", thirdNum);


// 17. Check Divisibility by Both 3 and 5
let value = 15;

if (value % 3 == 0 && value % 5 == 0)
    console.log("Divisible by both 3 and 5");
else
    console.log("Not divisible by both");


// 18. Calculate Factorial Using a For Loop
let factorialNum = 5, fact = 1;

for (let i = 1; i <= factorialNum; i++) {
    fact *= i;
}

console.log("Factorial:", fact);


// 19. Print Numbers from 50 to 1 in Reverse Order
for (let i = 50; i >= 1; i--) {
    console.log(i);
}


// 20. Sum of All Odd Numbers Between 1 and 100
let oddSum = 0;

for (let i = 1; i <= 100; i += 2) {
    oddSum += i;
}

console.log("Sum of odd numbers:", oddSum);
