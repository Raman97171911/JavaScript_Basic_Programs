**Questions**
1. Number is Even or Odd.
2. Factorial of a number.
3. Prime Number (Logic 1).
4. Prime Number (logic 2).
5. Largest Among n digit.
6. Swap two number.
7. Swap without using third variable.
8. Factorial of each number 1 to n.
9. All Prime numbers b/w 1 to n.
10. Sum of digit.
11. Power of Given Number.
12. Count the digit in a number.
13. Random Number Generator.
14. Area of Circle.
15. Area of Triangle.
16. Area of Rectangle.
17. Area of Square.
18. Volume of Sphere.
19. Volume of Cone.
20. Volume of Cuboid.

---
```html
<!-- // Number is Even Or Odd. -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Even Odd Number</title>
</head>
<body style="text-align:center; font-size:20px;">
<h2>JavaScript Program</h2>
<h3>Even Odd Number</h3>
Enter a number: <input id="number"><br><br>
<button onclick="evenodd()"> find out </button>
<p id="res"></p>
<script>
function evenodd()
{
    var number=document.getElementById("number").value;
    if(number % 2 == 0)
    {
        document.getElementById("res").innerHTML="Number is Even";
    }
    else
    {
        document.getElementById("res").innerHTML="Number is Odd";
    }
}
</script>
</body>
</html>
```
```javascript
// Number is even odd
const number = prompt("Enter a number: ");
if(number % 2 == 0)
{
    console.log("Number is Even.");
}
else
{
    console.log("Number is Odd.");
}
```
---
---
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Factorial of a number</title>
</head>
<body>
    <h1>Factorial of a number</h1>
    Enter a number: <input id="number"><br><br>
    <button onclick="factorial()">Find Out</button>
    <p id="res"></p>
    <script>
        function factorial()
        {
            let num = document.getElementById("number").value;
            let fact = 1;
            for (let i = 1;i<=num;i++)
        {
            fact*=i;
        }
        document.getElementById("res").innerHTML="Factorial is: "+fact;
        }
    </script>
</body>
</html>
```
```javascript
const number = prompt("Enter a number: ");
let fact=1;
for (let i=1;i<=number;i++)
{
    fact*=i;
}
console.log(`The factorial of ${number} is ${fact}.`);
```
---
---
