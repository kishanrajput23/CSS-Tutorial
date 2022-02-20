# Chapter 3 CSS Box Model

- The CSS box model looks at all the HTML elements as boxes

<img src="https://api.codewithharry.com/media/videoSeriesFiles/courseFiles/css-in-one-video/base64.png" alt="">

### Setting Width & Height

- We can set width and height in CSS as follows
```
#box {
    height: 70px;
    width: 70px;
}
```

- Note that the total width/height is calculated as follows:

- Total height = height + top/bottom padding + top/bottom border + top/bottom margin

### Setting Margin & Padding

- We can set margin and padding as follows:
```
.box{
    margin: 3px;        /* Sets top, bottom, left & right values*/
    padding: 4px;       /* Sets top, bottom, left & right values*/
}
```

```
.boxMain{
    margin: 7px 0px 2px 11px;      /*top, right, bottom, left*/
}
```

```
.boxLast{
    margin: 7px 3px;           /*(top & bottom) (left & right)*/
}
``` 

We can also set individual margins/padding like this:

- margin-top: 70px
- margin-bottom: 3px
- margin-left: 8px
- margin-right: 9px

Same goes with padding also

### Setting Borders

- We can set the border as follows
```
.bx{
    border-width: 2px;
    border-style: solid;
    border-color: red;
}
```

- Shorthand for above codes,
```
set border: 2px solid red;
``` 

### Border Radius

- We can set border-radius to create rounded borders
```
.div2{
    border-radius: 7px;
}
```

### Margin Collapse

- When two margins from different elements overlap, the equivalent margin is the greater of the two. This is called margin collapse.

<img src="https://api.codewithharry.com/media/videoSeriesFiles/courseFiles/css-in-one-video/base64_gEcQ5FF.png" alt="">

### Box Sizing

- Determines what out of padding and border is included in elements width and height
- Can be content-box or border-box
- Include only content in width/height

```
.div1{
    box-sizing: border-box;
}
```

- The content width and height includes, content + padding + border

## Chapter – 3 (Practice Set)

1. Create a website layout. Add a header box, one content box, and one footer.
2. Add borders and margins to question 1 (website layout)
3. Did the margin collapse between the content box and footer?
4. Add the box-sizing property to the content box. What changes did you notice?
