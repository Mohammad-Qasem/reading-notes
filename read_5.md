# CSS Associates Style rules with HT ML elements
CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

![declaration](https://djnmarti.com/foothill/coin65/week_02/images/anatomy_css_rule.gif)

## So we can see it consist of 
1-Selectors indicate which element the rule applies to.The same rule can apply to more than one element if you separate the element names with commas.

2-Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.

## How to make css effect on your html.

you should make a file with (.css) extention, and in your html file you should write the reference code of the css style to create that effict as the following

                <link href="css/example.css" type="text/css"rel="stylesheet" />

wehre the tag **link** under the tag <head> should be used to make the effect.
  

some of the following table will help yo to write your code in Css file:

Selector | Meaning | Example 
------------ | ------------- | ------------ 
Universal Selector | Applies to all elements in the document | * { } Targets all elements on the page
Type Selector | Matches element names | h1, h2, h3 { } Targets the 'h1 h2 and h3' elements 
Descendant Selector | Matches an element that is a descendent of another specified element (not just a direct child of that element) | p (a) { } Targets any a elements that sit inside a (p) element, even if there are other elements nested between them.


### more detaled examble

* for HTML

                           <div class="page">
                           <h1>Potatoes</h1>
                           <p>There are dozens of different potato
                              varieties.</p>
                           <p>They are usually described as early, second
                              early and maincrop potatoes.</p>
                           </div>
                           
* for CSS                          
                            
                            body {
                            font-family: Arial, Verdana, sans-serif;
                            color: #665544;
                            padding: 10px;}
                           .page {
                            border: 1px solid #665544;
                            background-color: #efefef;
                            padding: inherit;}
                           
                           
Note: you can see numbers like #665544 and these represents the color you need , and you can just google it to find whatever you need. 





