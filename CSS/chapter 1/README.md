# Learning CSS - Notes

*  CSS is called Cascading Style Sheet

* Linking CSS Files  to HTML 

```html
<link rel="stylesheet" href="./css/style.css">
```
- There are 3 types of CSS

1) Inline: It is written inside the html tag
   
```html
<p style="color:black"> Hii I am learning CSS </p>
```
   

2) Internal: It is written under the head section of .html file.
   
```
Syntax:
<head>
   <style>
          CSS Properties
   </style>
</head>
``` 

3) External: It is written by creating new .css file
   
- CSS Anatomy: Here p is called **Selector** , color is called **Property**, black is called **Property-value** and the entire thing is called **Declaration**
  
```css
p {
    color : black;
}
```

- Specificity In CSS: Specificity in css is used for selecting which property will be applied on a particular element if there are two or more properties applied to same the element

  
  a) **element**: It can be any html tag which has lowest specificity.

  
  b) **class**: It is an attribute which is not unique.

  c) **id**: It is an attribute which is unique and can only be used once and has highest specificity.

```
Specificity Order: Id > class > element
```
- !important: It can be used to overrule the specificity order and display the property value. But it is not considered to be used mostly.
```
Example
p {
     color: red !important;
}
```

- CSS Properties

1) Colors: The color property is used to give color to the web page or an element.

   a) background-color: It is used for back-ground color of the web page or an element.
```
   eg: background-color: red;
```
   b) color: It is a property to provide color to an element. It can also be written in rgb values where **rgb** stands for red , green, and blue and its value can go from o-255. Also there is a value **a** which stands for alpha which means opacity and its value can go from 0-1.
```
   eg: color: black;
    
       color: rgb(255,255,255);

       color: rgba(255, 0, 0, 0.5);
```
 The color can also be represented by hex-decimal code which values can go from 0-F
```
eg: color: #FFFFFF; - It corresponds to whte color. It can be also written using shorthand #FFF.

    color: #F00 - It corresponds to red color.
```
The another way to write the color is the **hsl** which stands for hue , saturation and lightness where hue value can go from 0-360 degree where 0 is red, 120 is green and 240 is blue, ,saturation value can go from 0-100% which means 0% is shade of gray and 100% is full color and lightness value can go from 0-100% which means 0% is black and 100% is white.

```
eg: color: hsl(224, 50%, 75%);
    
    color: hsla(120, 50%, 100%, 0.5); - Here a means alpha which is for opacity.
```


2) CSS Units
   
   a) font-size: It is used for font-sze of an element. There are 2 types of units :



   1] *Absolute units*: The absolute units are the units which are independent like **pixels(px)** and are not depended on another element for its size.


   2] *Relative units*:The relative units is the units which depends on another element like **%** and its will change respect to main element.

3. **CSS Box Model**
   
   The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

   a) *content*: The content of the box where text and images appear

   b) *width & height*: These properties define size of box.
   
   c) *padding*: It adds extra space around content inside an HTML element.

   d) *border*: It creates a line around an HTML element.

   e) *margin*: It defines space between two elements. Margin is transparent and does not show up when we see it in browser window.

```
Order of CSS Box Model Inside To Out
Content -> Padding -> Border -> Margin
```
```
Order of side properties are in clockwise-direction : Top> Right> Bottom> Left
```
- Outline: It is similar to border property which is not included in css box model but does not take up space.

eg: outline: 5px solid purple;

The outline has another property called outline-offset which can also take negative values.

- Typography: It is the way text is arranged and presented 

