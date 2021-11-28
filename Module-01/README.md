## Module 1 Practice

### 01. Variables

```
// Create two variables, firstName and lastName
let firstName = "Per"
let lastName = "Borgen"
// Concatenate the two variables into a third variable called fullName

let fullName = firstName + " " + lastName

// Log fullName to the console
console.log(fullName)
```

Output:

```
Per Borgen
```

---

### 02. Concatenating two strings in a function

```
let name = "Linda"
let greeting = "Hi there"

// Create a function that logs out "Hi there, Linda!" when called

function greetLinda() {
    console.log(greeting + ", " + name + "!")
}

greetLinda()
```

Output:

```
Hi there, Linda!
```

---

### 03. Incrementing and Decrementing

```
let myPoints = 3

// Create two functions, add3Points() and remove1Point(), and have them
// add/remove points to/from the myPoints variable

function add3Points() {
    myPoints += 3
}

function remove1Points() {
    myPoints -= 1
}

add3Points()
add3Points()
add3Points()
remove1Points()
remove1Points()

// Call the functions to that the line below logs out 10
console.log(myPoints)
```

Output:

```
10
```

---

### 04. Strings and Numbers

```
// Try to predict what each of the lines will log out
console.log("2" + 2) // "22"
console.log(11 + 7) //  18
console.log(6 + "5") // "65"
console.log("My points: " + 5 + 9) // "My points: 59"
console.log(2 + 2) // 4
console.log("11" + "14") //  "1114"
```

Output:

```
22
18
65
My points: 59
4
1114
```

---

### 05. Rendering an error message

index.html

```
<html>
    <head>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <img src="images/shoe.jpeg" alt="Nike shoe">
        <p>Nike shoe</p>
        <button onclick="purchase()">Purchase - $149</button>
        <p id="error"></p>
        <script src="index.js"></script>
    </body>
</html>
```

index.js

```
// When the user clicks the purchase button, render out
// "Something went wrong, please try again" in the paragraph
// that has the id="error".

let errorParagraph = document.getElementById("error")
console.log(errorParagraph)

function purchase() {
    console.log("button clicked")
    errorParagraph.textContent = "Something went wrong, please try again"
}
```

---

### 06. Calculator Challenge
