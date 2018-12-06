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
       /* Where the SVG will be styled */   
     </style> 
   
    </head>  
   
   <body>  
      Where the SVG will go...  
   </body>

</html>

```
### Part 3: Creating the SVG

For this example I am going to create 3 SVG:
 1. An Ellipse 
 2. A Polygon
 3. Text

#### Example 2. A Polygon
 ```
<!DOCTYPE html>
<html>
<body>

<svg height="250" width="500">
  <polygon points="130,40 500,90 250,100 123,210" style="fill:LightSteelBlue;stroke:LightSlateGrey;stroke-width:2" />
  Sorry, your browser does not support inline SVG.
</svg>

</body>
</html>
```
 
 
 

  
