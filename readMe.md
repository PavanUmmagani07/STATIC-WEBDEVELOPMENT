<!--HTML STRUCTURE-->
<!DOCTYPE html>
<html>
    <head>
        <body>
            Your code goes here
            ....
            ......
        </body>
    </head>
</html>


<!--HTML Element-->
<tag>Context(Text)</tag>

<tag>-> Start tag 
Context(Text)->Content
</tag>-> End tag

<!--Heading Element-->
<h1>Tourism</h1>
<h1>->Start tag
Tourism ->Content    
</h1>->End tag


<!--Paragrah Element-->
<p>Plan your trip wherever you want to go</p>
<p>->Start Tag
Plan your trip whereever you want-> Content    
</p>-> End Tag

<!--Button Element-->
<button>Get Started</button>
<button>->Start tag
Get Started ->Context
</button>->End tag

/*
A css file will be created. it is a list of RULESETS.
Each Ruleset Loo likes 
selector{
        property1: value1;
        property2: value2;
        }
*/

/*EXAMPLE*/
.h-center{      /*|->VALUE*/
    text-align: center;
    /*|->Property*/
}


/* ATTRIBUTE
With the help of Attributes,We can combine HTML and CSS
Attributes provide additional information about the HTML Element
Ex: Colour, TextSize, shape,underlines,etc..
*/

<!--HTML ATTRIBUTE-->
<tag attribute="value">Content</tag>

<!--Container-->
TO wrap all the required elements at one place, we use container element


<!--Styling with HTML-->
#EXAMPLE 
<h1 style="color: blue;">Tourism</h1>


<!--1. Font Family-->
The CSS font-family property specifies the font for an element.
#EXAMPLE
.main-heading {
    font-family: "Roboto";
  }
  .paragraph {
    font-family: "Roboto";
  }

 
CSS
You can use one of the below values of the font-family property,


Note
To use font families, you need to import their style sheets into your CSS file.
There shouldn't be any spelling mistakes in the values of the font-family property.
There must be quotations around the value of the font-family property.

<!--2. Font Size-->

The CSS font-size property specifies the size of the font.

#EXAMPLE
.main-heading {
    font-size: 36px;
  }
  .paragraph {
    font-size: 28px;
  }

Note
You must add px after the number in the value of the font-size property.
There shouldn't be any space between the number and px.
There shouldn't be any quotations around the value of the font-size property.


<!--3. Font Style-->

The CSS font-style property specifies the font style for a text.

You can use one of the below values of the font-style property,

Value
normal
italic
oblique

#EXAMPLE
.main-heading {
    font-style: italic;
  }
  .paragraph {
    font-style: normal;
  }



Note
There shouldn't be any spelling mistakes in the values of the font-style property.
There shouldn't be any quotations around the value of the font-style property.


<!--4. Font Weight-->
The CSS font-weight property specifies how thick or thin characters in text should be displayed.

#EXAMPLE
.main-heading {
    font-weight: bold;
  }
  .paragraph {
    font-weight: 200;
  }

You can use one of the below values of the font-weight property,

Value
normal
bold
bolder
lighter
100
200
300
400
500
600
700
800
900
Note
There shouldn't be any spelling mistakes in the values of the font-weight property.
There shouldn't be any quotations around the value of the font-weight property.
The numerical values given to the font-weight property must be in the range from 100 to 900 and should be the multiples of 100.

<!--5. Text Decoration-->

The CSS text-decoration property specifies the decoration added to the text.
#EXAMPLE
.main-heading {
    text-decoration: underline;
  }
  .paragraph {
    text-decoration: overline;
  }

You can use one of the below values of the text-decoration property,

Value	       Description
underline	   Underline the text
line-through   Strike through the text
overline	   Overline the text

Note
There shouldn't be any spelling mistakes in the values of the text-decoration property.
There shouldn't be any quotations around the value of the text-decoration property.
Ensure that text-decoration and line-through are hyphenated.

<!--CSS BOX MODEL-->
Every HTML element on a web page is  a rectangular box.

Each Rectangular box has different properties:
->Height 
->Width 
->Margin (whatever present beyond the HTML box is known as margin by default it will be 0px)
->border 
->padding 

<!--Height&Width Example-->
.h-center{
    height:100px;
    Width:150px;
}
<!--Adding Background Image-->
.card{
    background-image: url("IMAGE URL");
}

<!--Viewport-->
The browser's viewport is the area of the window in which web content can be seen.

<!--1. Viewport Height-->
The CSS Viewport Height vh Unit equals to 1% of the height of the Viewport (browser window size).
#EXAMPLE
.card {
    height: 50vh;
  }

Note
The height 100vh sets an HTML element to the entire height of the Viewport (browser window size).

2. Viewport Width
The CSS Viewport Width vw Unit equals to 1% of the width of the Viewport (browser window size).
#EXAMPLE
.card {
    width: 100vw;
  }

Note
The width 100vw sets an HTML element to the entire width of the Viewport (browser window size).

<!--Background-Size-->
The CSS background-size property specifies the size of the background image of an HTML element.
#EXAMPLE
.card {
    background-size: cover;
  }


Value	Description
cover	Scales the image to the smallest size while maintaining the same aspect ratio (width/height) and covers the entire width and height even if the image is cropped.

Aspect Ratio is the ratio of the width and Height (width/height) of an image

