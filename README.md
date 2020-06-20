# Lesson 2: Introduction To CSS

### Introduction
<p>
  In this lesson, we will learn about the second of the three languages called CSS. We will learn about the three ways we can include css into our HTML file, and their drawbacks. We will also learn hot to use CSS to style our elements even when they are nested. It helps to metaphorically think of CSS as the styling of a webpage. it is only concerned with describing how things are present on the webpage.
</p>

### Lesson Objectives:
At the end of this lesson you will be able to answer the following questions:
- What does CSS stand for?
- What is CSS used for?
- What does a CSS document look like?
- How do we include CSS in our HTML code?
- What is the syntax of CSS?
- How do you target nested elements with CSS selectors?
- What are the most commonly used CSS properties?

### The Three Ways of using CSS in your HTML elements
<p>
  There are three ways of including CSS in your HTML and they are:
</p>

- Inline CSS
- Internal CSS
- External CSS


### Syntax

##### General CSS Syntax

```css

selector {
  property-one: value;
  property-two: value;
}

```

### Lesson Terminology:
- usage: 
  - inline css
  - internal css
  - external css
- selectors: 
  - element
  - class
  - id

##### Inline CSS
```html
<element style="property-one: value;" > content </element>
```


##### Internal CSS
```html
<head>
  <style>

    .class-selector-name {
      property-one: value;
    }

    #id-selector-name {
      property-one: value;
    }

  </style>
</head>
<body>
  <element id="id-selector-name" class="class-selector-name" > content </element>
</body>
```

##### External CSS
```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <element id="id-selector-name" class="class-selector-name" > content </element>
</body>
```

### CSS Selector Types

```css

tag-name {
  property-one: value;
  property-two: value;
}

#id-selector {
  property-one: value;
  property-two: value;
}

.class-selector {
  property-one: value;
  property-two: value;
}

```


#### TEST 001
- What does CSS stand for?
- How many ways are there to include CSS into your HTML elements?
- Explain how these three ways of including CSS into your HTML elements works.
- What is the syntax of a CSS style definition? (name the parts)
- What are the most commonly used CSS selectors?
- What are the advantages and disadvantages of the following concepts:
  - Inline CSS
  - Internal CSS
  - External CSS
- What CSS two attribute controls spacing in and outside of an element?
- What is the difference between the CSS attributes color and background-color?
- Name 5 CSS attributes that you think will be most useful and explain how you would use them?
- If a CSS class is defined in more than one place, which one of them will affect the appearance of your HTML element?
- How many ways do we have to define color in CSS?
- What is the difference between padding and margin?
- How can we write the hexadecimal value shorter in CSS FFFFFF?
- What color does FFFFFF represent?
