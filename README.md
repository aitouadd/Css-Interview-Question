# Css-Interview-Question
1.  ***Why we use box-sizing in css ?***


The CSS box-sizing property allows us to ***include*** the padding and border in an element's total width and height.


2. ***What are breakpoint for viewport responsive device ?***


In responsive web design, viewport breakpoints are ***browser dimensions (usually just widths) that set the active range of a given media query***. Once the browser dimensions are within that range, the styles associated with that media query will apply.



3. ***How to make website responsive ?***


1.Set Appropriate Responsive Breakpoints.

2.Start with a Fluid Grid.

3.Take touchscreens into consideration.

4.Define Typography.

5.Use a pre-designed theme or layout to save time.

6.Test Responsiveness on Real Devices.



   4. ***What is pseudo selector in css ?***
  
1.CSS Pseudo-classes:
 
 A pseudo-class is used to define a special state of an element.
 
 **For example***, it can be used to:

1.Style an element when a user mouses over it

2.Style visited and unvisited links differently

3.Style an element when it gets focus

***Syntax:***

            selector:pseudo-class {
            
             property: value;
             
             }

  Click [Her](https://www.w3schools.com/css/css_pseudo_classes.asp) To Learn more about CSS Pseudo-classes



2.CSS Pseudo-elements:
  
  A CSS pseudo-element is used to style specified parts of an element.

  For example, it can be used to:

  1.Style the first letter, or line, of an element
  
  2.Insert content before, or after, the content of an element
  
  The syntax of pseudo-elements:
  
***Syntax:***
            
           selector::pseudo-element {
                     property: value;
           }

  Click [Her](https://www.w3schools.com/css/css_pseudo_elements.asp) To Learn more about CSS Pseudo-elements
  
  
5. ***What is flex box in css?***

[Basic concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)

[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)


6. ***What is difference between PX,unit,em,rem in css ?***

   The difference between rem units and em units is that em units are relative to the font size of their own elemen

  ![Ednn_SgWkAIC6mf](https://user-images.githubusercontent.com/98220932/207608098-e2fc9028-9245-4754-850c-8182efe6dea0.jpg)


7. ***What is bom in css ?***

The Browser Object Model (BOM) allows JavaScript to "talk to" the browser.

[What's DOM (Document Object Model) & DOM VS BOM (Browser Object Model) - JavaScript DOM](https://www.youtube.com/watch?v=vXqe3BfiK90&list=PLpXCAa5_ykleN-CRRLDBwL-eBYWqdsgpc)


8. ***What is different position in css ?***

There are five different position values:

***1***. static:

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page
[let's go to the practice](https://www.w3schools.com/css/tryit.asp?filename=trycss_position_static)


***2***.relative:

An element with position: relative; is positioned relative to its normal position.
[let's go to the practice](https://www.w3schools.com/css/tryit.asp?filename=trycss_position_relative)


***3***. fixed:

An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top,       right, bottom, and left properties are used to position the element.[let's go to the practice](https://www.w3schools.com/css/tryit.asp?filename=trycss_position_fixed)                


***4***. absolute:

An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

***Note:*** Absolute positioned elements are removed from the normal flow, and can overlap elements.

[let's go to the practice](https://www.w3schools.com/css/tryit.asp?filename=trycss_position_absolute)




***5***. sticky:

An element with position: sticky; is positioned based on the user's scroll position.

[let's go to the practice](https://www.w3schools.com/css/tryit.asp?filename=trycss_position_sticky)


9. ***What is media query in css ?***

Media queries in CSS3 extended the CSS2 media types idea: Instead of looking for a type of device, they look at the capability of the device.

Media queries can be used to check many things, such as:

@ width and height of the viewport

@ width and height of the device

@ orientation (is the tablet/phone in landscape or portrait mode?)

@resolution

Using media queries are a popular technique for delivering a tailored style sheet to desktops, laptops, tablets, and mobile phones (such as iPhone and Android phones).

 ***Media Query Syntax***
 
        @media not|only mediatype and (expressions) {
          CSS-Code;
        }
        
 look at this exemple to understanding how it works [her](https://www.w3schools.com/css/tryit.asp?filename=trycss3_media_queries1)       




CSS3 Media Types :

| Value   | Description                                          | 
| ------- | ---------------------------------------------------- |
| all	    |   Used for all media type devices                    |
| print	  |   Used for printers                                  |
| screen	| Used for computer screens, tablets, smart-phones etc.|
| speech	| Used for screenreaders that "reads" the page out loud|




10. ***What is difference between css and css3 ?***
  

Key Difference Between CSS and CSS3:

The main difference between CSS and CSS3 is that CSS3 has ***modules***. CSS is the ***basic version***, and it does not support responsive design. CSS3, on the other hand, is the latest version and supports responsive design. CSS ***cannot*** be split into modules, but CSS3 ***can*** be split into modules.





***happy coding***




     



       
       
