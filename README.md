# JS-22-11-24

# Funktioner

Vad skrivs ut av följande koder?

a) `function foo() {`
`console.log("test");`
`}`
`foo("hej");`

b) `let a = foo(3);`
`console.log(a);`
`function foo(i) {`
`return i * i;`
`}`

c) `console.log( foo(3, 5) );`
`function foo(x, y) {`
`return x * y;`
`}`

d) `let x = 2;`
`let y = 3;`
`let a = foo(foo(x) + foo(y));`
`console.log(a);`
`function foo(i) {`
`return 5n* i;`
`}`

e) `let a = 5;`
`function foo(a) {`
`a++;`
`}`
`a += 2;`
`console.log(a);`

f) `var foo = function(i) {`
`return 2 * i * i;`
`};`
`var goo = function(x, y) }`
`return x(y);`
`};`
`var a = goo(foo, 3);`
`console.log(a);`

g) Skriv en funktion som tar en parameter med namnet "name" att skriva ut. Om funktionen till exempel anropas med strängen "Cecilia" ska den skriva ut: "Hej Cecilia!".

h) Skriv en funktion som tar en string som parameter. Funktionen ska returnera de tre första tecknen. [Tips:](https://www.w3schools.com/jsref/jsref_substring.asp)
