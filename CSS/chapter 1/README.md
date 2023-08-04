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

