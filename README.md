# Lesson 2: Introduction To CSS

<p>
In this lesson, we will learn about the second of the three languages called CSS. It helps to metaphorically think of CSS as the styling of a webpage. it is only concerned with describing how things are present on the webpage.
</p>

```css

selector {
  property-one: value;
  property-two: value;
}

```


### Lesson Terminology:
- selectors 
- tags
    - opening
    - closing
    - self-closing
- attributes:
    - name
    - value
- comments

#### Elements
<p>
An HTML page is just a collection of elements arranged in special ways. An element is made up of smaller parts. These smaller parts are: tags, attributes and content.
Below are some rules for elements:
</p>

### Lesson Terminology:
- elements may or may not have a closing tag, but they always have a opening tag.
- elements may or may not have attributes.
- elements may or may not have content. 

### Lesson Objectives:
At the end of this lesson you will be able to answer the following questions:
- What is HTML?
- What is HTML used for?
- What does an HTML document look like?
- What are the parts of an HTML document and what does each part describe?
- What is an HTML element?
- What parts can an HTML element have and what does each part do?
- What are the most commonly used HTML elements? (name then and also specify if they have a closing tag)

### HTML ELEMENTS:

#### Basic HTML Document Structure:
```html 
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>

        <h1>This is a Heading</h1>
        <p>This is a paragraph.</p>

    </body>
</html>
```

#### Signle and Multiline Comments:
```html 
<!-- This is a commnent and will not be rendered on the webpage -->
```

#### Text Formatting:
```html 
<p>I and am a P tag</p>
<h1>I and am an H1 tag</h1>
<h2>I and am an H2 tag/h2>
<h3>I and am an H3 tag</h3>
...
<h6>I and am an H46 tag</h6>
```

```html 
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Small text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```


#### Anchor Tag:
```html 
<a href="https://www.baidu.com/">Go to Baidu</a>
<a href="filename.html">Go to Youku</a>
```

#### Image Tag:
```html 
<img src="filename.jpg" alt="text that you will see if image was not found" width="104" height="142">
```

#### Button Tag:
```html 
<button>Button Name</button>
```

#### Ordered & Unordered Lists Tag:
```html 
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

#### Table Tag:
```html 
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>David</td>
    <td>Chen</td>
    <td>27</td>
  </tr>
  <tr>
    <td>Thomas</td>
    <td>Su</td>
    <td>10</td>
  </tr>
</table>
```

#### Table Tag:
```html 
<iframe src="https://www.baidu.com/" height="200" width="300"></iframe>
```
### HTML Forms
#### Form Tag:
```html 
<form>
.
form elements
.
</form>
```

#### Form Elements:
```html 
<form>
    <input type="text">
    <input type="radio">
    <input type="submit">

    <select id="cars" name="cars">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
        <option value="fiat">Fiat</option>
        <option value="audi">Audi</option>
    </select>

    <textarea name="message" rows="10" cols="30">
        The cat was playing in the garden.
    </textarea>
</form>

<form action="/action_page.php">
    <fieldset>
        <legend>Personalia:</legend>
        <label for="fname">First name:</label><br>
        <input type="text" id="fname" name="fname" value="John"><br>
        <label for="lname">Last name:</label><br>
        <input type="text" id="lname" name="lname" value="Doe"><br><br>
        <input type="submit" value="Submit">
    </fieldset>
</form>
```

#### Input Types Tag:
```html 
<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text">
<input type="time">
<input type="url">
<input type="week">
```