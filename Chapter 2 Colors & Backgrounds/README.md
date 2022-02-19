# Chapter – 2 (Colors & Backgrounds)

- CSS rules are simple key-value pairs with a selector. We can write CSS rules to change color and set backgrounds.

### The color property

- The CSS color property can be used to set the text color inside an element
```
p {
    color: red;            /*Text color will be changed to red*/
}
```
- Similarly, we can set color for different elements

### Types of color values

Following are the most commonly used color values in CSS

- RGB: Specify color using Red, green, blue values. E.g. rgb(200,98,70)
- HEX Code: Specify color using hex code. E.g. #ff7180
- HSL: Specify the color using hsl values. E.g. hsl(8,90%,63%)

HSL stands for Hue, saturation, and lightness

The value of the color or background color is provided as any one of these values.

**Note:** We also have RGBA and HSLA values for color but they are rarely used by beginners. A stand for alpha

### The background-color property

- The CSS background-color property specifies the background color of a container.
- For e.g.

```
.brown {
    background-color: brown;
}
```

### The background-image property
- Used to set an image as the background
```
body {
    background-image: url(“harry.jpg”)
}
```
- The image is by default repeated in X & Y directions

### The background-repeat property

Can be any of:

- repeat-x : repeat in the horizontal direction
- repeat-y : repeat in the vertical direction
- no-repeat : image not repeat

See more possible values at MDN docs

### The background-size property

Can be following:

- cover : fits & no empty space remains
- contain : fits & image is fully visible
- auto : display in original size
- {{width}} : set width & height will be set automatically
- {{width}} {{height}} : set width & height

**Note:** Always check the MDN docs to dissect a given CSS property. Remember, practice will make you perfect

### The background-position property
- Sets the starting position of a background image
```
.div1{
    background-position: left top;
}
```

### The background-attachment property
- Defines a scrollable/non-scrollable character of a background image
```
.div2{
    background-attachment: fixed
}
```

### The background shorthand
- A single property to set multiple background properties
```
.div3{
    background: red url(‘img.png’) no-repeat fixed right top;
}
```

One of the properties can be missing given the others are in order.

- {{width}} {{height}} : set width & height

**Note:** Always check the MDN docs to dissect a given CSS property. Remember, practice will make you perfect

### The background-position property:
- Sets the starting position of a background image
```
.div1{
    background-position: left top;
}
```

### The background-attachment property
- Defines a scrollable/non-scrollable character of a background image.
```
.div2{
          background-attachment: fixed;
}
```

### The background shorthand
- A single property to set multiple background properties
```
.div3{
          background: red url(‘img.png’) no-repeat fixed right top;
}
```

One of the properties can be missing given the others are in order.


## Chapter – 2 (Practice Set)

1. Create a dark blue navigation bar with light color items.
2. Change the color of the main container on your page to dark red.
3. Create a div and add a background image with a given width and height.
4. Create a vertical box and add a fixed non-scrolling background to it.
5. Verify that the background shorthand property works with some of the values skipped.
