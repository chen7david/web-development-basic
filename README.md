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
