# Chapter – 1 (Creating our first CSS Website)

- We will create our first CSS website in this section.

### What is DOM?

- DOM stands for document object model. When a page is loaded, the browser creates a DOM of the page which is constructed as a tree of objects.

### HTML id and class attributes

- When an HTML element is given an id, it serves as a unique identifier for that element.
- On the other hand, when an HTML element is given a class, it now belongs to that class. More than one element can belong to a single class but every element must have a unique id (if assigned).
- We can add multiple classes to an element like this,
```
<div id = ‘first’ class = ‘C1 C2 C3’>
          …
</div>
```

- first is the unique id

- C1, C2 and C3 are the multiple classes followed by spaces


### Three ways to add CSS to HTML

- There are 3 ways to add CSS to HTML:

1. <style> tag : Adding <style> … </style> to HTML
2. Inline CSS : Adding CSS using style attribute
3. External CSS : Adding a stylesheet(.css) to HTML using <link> tag
 
### CSS Selectors

- A CSS Selector is used to select an HTML element(s) for styling
```
body {
    color: red;             /* Declaration (property: value) */
    background: pink;       /* Declaration */
}
```
- body is the selector

### Element Selector

- It is used to select an element based on the tag name
- For example:
```
h2 {
    color: blue;
}
```

### Id Selector

- It is used to select an element with a given id
- For example:
```
#first {
    color: white;
    background: black;
}                               /* ‘#’ is used to target by id */
```

### Class Selector

- It is used to select an element with a given class
- For example:
```
.red {
    background: red;
}
``` 

### Important Notes:

- We can group selectors like this:
  
```
h1,h2,h3,div {
    color:blue;           /*h1, h2, h3 and div will be blue*/
}
```

- We can use element class as a selector like this:
  
```
p.red {
    color: red;          /*all paragraphs will get color of red*/
}
```
  
- '*' can be used as a universal selector to select all the elements
  
```
* {
    margin: 0;
    padding: 0;
}
``` 

- An inline style will override external and internal styles
 
### Comments in CSS

- Comments in CSS are the text which is not parsed and is thus ignored.

## Chapter – 1 (Practice Set)

1. Create a website with a class red div which has a background color of the red and color white.
2. Create an element with id head and verify that background color works on it as inline, external as well as using style tag CSS.
3. Create a CSS class one and verify that it works on multiple elements.
4. Create multiple CSS classes and verify that all of these work on the same element.
5. Have a look at the MDN CSS reference and try to play around with few key-value CSS rules.
