### Web Development Basic

# Lesson 3: What is JavaScript
<p>
In this course, we will learn the basics of web development. With these lessons, we hope to leave you with an intuitive understanding of the building blocks and the development architecture. We will learn by theory and example, giving you both an understanding and a hands-on experience of the fundamentals.
</p>

Data Types
- boolean
- integer
- string
- array
- object
- function

```js

let boolean = false

let integer = 1

let string = "hello world"

let array = ['apple', 'pear', 'mango']

let object = { 
    name: 'David',
    think: (idea) {
        return conclusion(idea)
    }
}

let function = function helloWorld(){
    console.log('Hello World')
}
```
##### Project 001 Random Colored Pixel
Follow the follwoign instructions:
1. Create the below folder structure
```bash
    ├── index.html
    ├── main.css
    └── main.js
```
2. In your index.html file write the following code
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="main.css">
    
</head>
<body>
    <div class="box"></div>
    <script src="main.js"></script>
</body>
</html>
```
3. In your main.css file write the following code
```css
.box{
    background-color: red;
    width: 500px;
    height: 500px;
    float: left;
}
```

4. In your main.js file write the following code
```js
let box = document.querySelector(".box")

function rand(limit){
    return Math.floor(Math.random() * limit)
}

function color(){
    return `rgb(${rand(255)},${rand(255)},${rand(255)})`
}

function changeBoxColor(){
    box.style.backgroundColor = color()
}

box.addEventListener('click', changeBoxColor)
```

Now lets start with lesson one where we will learn about HTML

