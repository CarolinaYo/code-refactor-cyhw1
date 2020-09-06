Title

Homework 1: HTML CSS Git: Code Refactor

INTRODUCTION

This is Homework 1 to "Introduction to Web Developement, HTML, CSS, and Git."  This is an individual homework with pre-written HTML and CSS code.  The goal of this activity is to refactor the given code and use semantic markup in the HTML design.

PURPOSE

This exercise serve as an introduction to coding best practice for new/junior developer. From my undestanding, some of the HTML tags serve the same purpose to the design of the page.  The difference lie on the meaning that each tags represent.  Implementing semantic markup in your code will help add proper structure to the code that will be easier for machine to read your content and will expand the accessiblity of your webpage.

CHALLENGES

My initial chalenge was my limited familiarity of Html tags. What help me tremendously is the information found on MDN web docs https://developer.mozilla.org/en-US/docs/Web/HTML.  I used the information on "HTML elements reference" as my guide.  

CHANGES

My first approach in this assignment is to apply proper semantic tags to the structure on the HTML.  I have applied <header><main><section><aside><footer> inplace of general <div> tag.  I added description to all of the images with the alt attribute.  In reducing some of the redundancy, I created a single class that consolidate repeated class functions.  
For example:

New class       | Class replaced
main-content    | search-engine-optimization
                | online-reputation-management
                | social-media-marketing
side-content    | benefit-lead
                | benefit-brand 
                | benefit-cost


Lastly, I re-organized the sequence of the HTML and CSS code and updated footer to the current year.


