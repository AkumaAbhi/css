https://developer.mozilla.org/en-US/docs/Web/CSS/Reference 

Three ways to add CSS to HTML

There are 3 ways to add CSS to HTML:

<style> tag : Adding <style> … </style> to HTML
Inline CSS : Adding CSS using style attribute
External CSS : Adding a stylesheet(.css) to HTML using <link> 


---------------------------------------------------------
CSS Selectors

A CSS Selector is used to select an HTML element(s) for styling
Element Selector
It is used to select an element based on the tag name

Id Selector
It is used to select an element with a given id

Class Selector
It is used to select an element with a given class
---------------------------------------------------------

Important Notes:

We can group selectors like this:
h1,h2,h3,div {
          color:blue;           /*h1,h2,h3 and div will be blue*/
}
 

We can use element class as a selector like this:
p.red {
          color: red;            /*all paragraphs will get color of red*/
}
 

* can be used as a universal selector to select all the elements
*  {
          margin: 0;
          padding: 0;
}

---------------------------------------------------------