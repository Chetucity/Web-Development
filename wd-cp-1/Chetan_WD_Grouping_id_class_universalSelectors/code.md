- HTML elements with class="center" will be red and center-aligned :straight_ruler:

```` html
<div>
<p id="green"> Hello I am Chetucity </p>
</div>

````
- In CSS Doc to style that Particular DIV we write as follows :straight_ruler:

``` css

#green {
    color: green;
}
```

```html
<html>
 <head>
 </head>
 <body>
   <div class="main">
     <h3>Welcome to Educative!</h3>
     <p id="demo">Sample paragraph with an ID</p>
     <p> Sample paragraph with no ID</p>
   </div>
 </body>
</html>
```

```css
.main {
  background-color: #FFAFA4;
}

#demo {
  background-color: #DEDAF7;
}
```

## Syntax
* The syntax for CSS grouping selector is as follows −

```css
element, element {
   /*declarations*/
}
```
The following examples illustrate CSS grouping selector −

```html
<!DOCTYPE html>
<html>
<head>
<style>
article, p, img {
   display: block;
   margin: auto;
   text-align: center;
   border-bottom: double orange;
}
</style>
</head>
<body>
<article>Demo Text</article>
<p>This is demo text.</p>
<br/>
<img src="https://chetucity.com">
</body>
</html>
```
![](https://www.tutorialspoint.com/assets/questions/media/34191/grouping_selectors.jpg)

## Output
This gives the following output −

![](https://www.tutorialspoint.com/assets/questions/media/34191/grouping_selectors_css.jpg)