## Complete Guide To HTML5

### HTML: It is HyperText Markup Language

```html
This is the basic structure of HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

#### It varies from h1 to h6 where h1 is the biggest and h6 is the smallest
```html
<h1> This is  largest heading tag </h1>
<h6> This is smallest heading tag </h6>
```
#### It is used to divide the page into section and allow to group the items to apply the same style
```html
<div> This is the division tag </div>
```
#### It is paragraph tag which is having the closing tag
```html
<p> This is paragraph tag </p>
```

#### It is line breaking tag. It is used to put paragraph sentence in next line and it doesn't have closing tag
```html
<br> This is line breaking tag
```
#### Attributes: It is used to give additional properties to a tag The attributes contain 2 parts: 1] name 2] value . There are two types of attributes:

```html
Syntax of attributes: <tagname attribute name = "attribute value">
```
##### 1) Boolean attributes: 

###### a) required: It is used to get details and it is mandatory
          eg: <input type= "text" required>

###### b) disabled: It is used for disabling the element and is not used afterwards
          eg: <input type= "text" disabled>

##### 2) General attributes:

###### a) Id: It is an attribute which is used to give unique name to an element
       eg: <tagname id = "attribute value">

###### b) Class: It is as same as Id attribute but not a unique name.
       eg: <p class ="first"
       
#### It is a horizontal tag which is used to give a horizontal line in the HTML document

```html
   <hr> This will give a horizonatal line in a HTML document </hr>
```

##### In HTML document browser ignores whitespacing/spacing for a element. So for giving a spacing in the HTML document we use something called **HTML Entities** which is used to dispaly reserved characters in HTML. With the help of HTML entities we can dispaly reserved characters, special characters, emojiis and symbols.

```html
Syntax of entities: &entity_name; OR  &#entity_number;
```
* &nbsp - whitespace 
* &lt - less than(<) 
* &gt - greater than(>) 
* &Backslash- (/)

#### Comments: It is used to make the understanding of code much better and easy for code review.The comments are not dispalyed in browser.

```html
   <!-- This is a comment in a HTML-->
```
###### For dispalying random text in p tag we use **lorem**


```html
  eg: <p> lorem 50 </p> 

  Here 50 is used to specify the number of words
```
#### It is used for bolding a text called bold tag
```html
  <b> Bold Tag </b>
```
#### It is used for bold & important called strong tag
```html
  <strong> This is a strong tag </strong>
```
#### It is used for italic called called emphasize tag
```html
  <em> This is a italic tag </em>
```
#### It is used for underlining the text called underline tag
```html
  <u> This is a underline tag </u>
```
#### It is used to make text smaller called small tag
```html
   <small> This is a small tag </small>
```
#### It is used for marking or highlighting the text called mark tag
```html
   <mark> ThIs is a mark tag </mark>
```
#### It is used for deleting the text called delete tag
```html
   <del> This is a delete tag </del>
```
#### It is used for displaying exponential values called superscript tag
```html
   eg: 10 <sup> 2 </sup> 

   Output - 10^2
```
#### It is used for displaying logarithmic values called subscript tag
```html
   eg: 10 <sub> 2 </sub>

   Output - 10 base 2
```
#### List Tag: It is used for listing the elements called li tag. It contains 2 list:

```html
   <li> This is a list tag </li>
```

##### 1) Ordered list: It is used to display order list with number, alphabet, etc.

```html
  <ol> This is a order list </ol>

  Order list: <ol>
                <li> DSA </li>
                <li> Development </li>
              </ol>

  Output: a) DSA
          b) Development
```
###### For changing a) & b) in a ordered list to 1) & 2) we use type attribute
```html
   <ol type= "A: for capital letters, a: for small letters, I: for roman big number, i: for roman small number"> </ol>
```
##### 2) Unordered list: It is used to display unorderd list with dot & square

``` html
    <ul> 
      <li> DSA </li>
      <li> Development </li>
    </ul>
```

##### Nesting - It is used to put one tag into another.

#### It is called span tag used for short pieces of content to separate them which are in a same line or other.

``` html
   <span> This is soan tag </span>
```

#### It is called image tag which is used to display the images in the browser. It is self-closing tag. It is has attributes like 

##### a) alt: It is used to describe the image or give caption it. It means alternative text which plays important role in SEO.

##### b) width & height: It is used to provide width and height to images and the unit used are % or px.

``` html
    Syntax- <img src="url of image or file name of image.extension" alt="It is a image tag" width="20%" height= "20%"/> 
```
#### It is called video tag used to display the videos in the web browser. 

##### Here attributes are width, height, controls (to give control to user), autoplay (to play automatically), loop (for playing video continously), muted (to mute the video), poster="url" (It is used to display thumbnail)

``` html
   Syntax- <video src= "url" width= "20px" height ="20px" autoplay poster="url of image" controls>
               Video Not Supported
           </video>
```
#### It is called anchor tag which is used to create link or hyperlink. Here attribute used is called *href* which is called hyperlink reference.

``` html
    Syntax- <a href="#"> Link </a>

    The # can include url of link or file name.extension

    If it is URL(Uniform Resource Locator) then called Absolute Path otherwise if file name is mentioned than it is Relative Path. For adding 
    relative path in a tag we use ./ before mentioning the file name.

    
```
#### For adding link to image

``` html
   
   <a href="url" target="_blank"> <img src ="url"/> </a>
   
   For making browser open in a new page we use target="_blank"
```
