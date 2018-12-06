# SVG Tutorial
<sup>Author: Jessica Sellers</sup>

<strong>Purpose:</strong> This tutorial will show people how to create a basic webpage in HTML5/CSS that contains SVG (Scalable Vector Graphics)

<strong>Target Audience:</strong> Anyone that has a very basic understanding of web development and coding



## Tutorial
### Part 1: Getting Started

First you will need to create a very basic webpage. For this you may want to download a code editor if you do not already have one. I suggest Brackets, you can download it [here.](http://brackets.io/)

Now open Brackets or whatever code editor you are using and create a new file named _SVG.html_

### Part 2: Adding HTML Tags 

We will now populate the _SVG.html_ file that you created with the basic HTML tags. 

These are:
  * ``` <!DOCTYPE html> ```which defines the document type
  * ``` <html> ```which defines the root of an HTML document
  * ```<head>``` which defines information about the document
  * ```<title>``` which defines a title for the document
  * ```<meta>``` which describes metadata within an HTML document
  * ```<style>``` which defines style information for an HTML document
  * ```<body>``` which defines the documents body (where the content is)
  
Below I have demonstrated the basic layout of an HTML document:

``` 
<!DOCTYPE html>
  <html>
    <head>
      
      <title>SVG Tutorial</title>  
      <meta charset="UTF-8">
   
     <style>   
       /* Where CSS usually goes */   
     </style> 
   
    </head>  
   
   <body>  
      Where the SVG will go...  
   </body>

</html>

```
### Part 3: Creating the SVG

For this example I am going to create 3 SVG:
 1. A Polygon 
 2. Rainbow Ellipses
 3. Text


#### Example 1. A Polygon
 ```
<!DOCTYPE html>
<html>
<body>

<svg height="250" width="500">
  <polygon points="130,40 500,90 250,100 123,210" style="fill:LightSteelBlue;stroke:LightSlateGrey;stroke-width:2" />
  I'm afraid your browser does not support SVG.
</svg>

</body>
</html>
```
In this example we declare the size of the svg in the <svg> element. Then we create a <polygon> element inside and use inline CSS to style it. The points attribute also inside the <polygon> element says what the x and y coordinates for each point are equal to. I added the text "I'm afraid your browser does not support SVG" as an error message so that if the SVG does not appear this error message does instead because not all browsers support SVG. Play around with this SVG, add more points if you would like and create your own polygon. 

#### Example 2. Rainbow Ellipses
```
<!DOCTYPE html>
<html>
<body>

<svg height="800" width="1200">
  <ellipse cx="320" cy="200" rx="340" ry="70" style="fill:red" />
  <ellipse cx="300" cy="180" rx="310" ry="60" style="fill:orange" />
  <ellipse cx="280" cy="150" rx="280" ry="50" style="fill:yellow" />
  <ellipse cx="260" cy="130" rx="250" ry="40" style="fill:green" />
  <ellipse cx="240" cy="100" rx="220" ry="30" style="fill:blue" />
  <ellipse cx="220" cy="70" rx="190" ry="20" style="fill:indigo" />
  <ellipse cx="210" cy="45" rx="170" ry="15" style="fill:violet" />
  I'm sorry to tell you that your browser does not support SVG. 
</svg>

</body>
</html>

```
 In this example I created 7 different ellipses and placed them on top of one another making them the color of the rainbow. I again created an <svg> element that declared the size of the svg and then created 7 <ellipse> elements inside. The cx and cy attributes define what the x and y coordinates are at the center of the ellipse. Then the rx and ry elements define what the horizontal and vertical radiuses are.
 
 

  
