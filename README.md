//this is a single line comment
/*this is multi line comment*/

//OPERATORS:

//1.Arithmetic operators 

let a = 5;
let b = 8;
console.log("a = 5","& b = 8");
console.log("a + b =", a + b); //Incrememt  13
console.log("a - b =", a - b); //Decrement -3
console.log("a * b =", a * b); //Mutliplication 40
console.log("a / b =", a / b); //Division 0.625
console.log("a % b =", a % b); //Modulus 5
console.log("a ** b =", a ** b); //Exponentiation 390625

// Number + String => Concatenation
let y =  5 + "hello";  
console.log( y );   //5hello

//string - number
let p = "Hello" - 1; 
console.log( p );  //NaN

// Infinity * 0
let x = Infinity * 0;
console.log(x); //NaN

//Infinity * Infinity
let t = Infinity * Infinity;
console.log(t); //Infinity

//string * number
let z = 'hi' * 2;  
console.log(z);  //NaN


//Unary operator

//1.Increment operator

a++;  //post increment 6
a++;   //7
++a;  //pre increment  8
a++;  //9
++a;  //10
console.log(a); //10

//2.Decrement operator

b--;  //post decrement  7
b--;  //6
--b;  //pre  decrement 5
--b;  //4
console.log(b); //4

//Assignment Operators
let m = 3;
let n = 4;
console.log(m += n);  //7   (m = m + n)
console.log(m -= n);  //-1   (m = m - n)
console.log(m *= n);  //12  (m = m * n)
console.log(m /= n);  //0.75   (m = m / n)
console.log(m %= n);  //1   (m = m % n)
console.log(m **= n); //81  (m = m ** n)

//Comparison Operators
let c = 3;
let d = 7;
console.log(c == d); //false
console.log(c != d); //true
console.log(c == d); //false if c is a number or d is a string
console.log(c === d); //false if c is a number or d is a string because === it is a strictly check
console.log(c !== d); //true if c is a number or d is a string because !== it is a strictly check
console.log(c > d);  //false
console.log(c <= d); //true
console.log(c >= d); //false
console.log(c < d);  //true

//Logical Operators
let e = 4;
let f = 5;
console.log(e < f && f > e); //true  Logical AND &&
console.log(e < f && f < e); //false

console.log(e < f || f > e); //true  Logical OR ||
console.log(e < f || f < e); //true
console.log(e > f || f < e); //false

console.log(!(e < f));  //false  Logical NOT !

