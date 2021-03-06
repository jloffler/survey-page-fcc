### freeCodeCamp Responsive Web Design Project

# Build a Survey Form

## Links to Live Website
 - https://jloffler.github.io/survey-page-fcc/
 - February 21, 2021
 
## Objective
Build a website using HTML and CSS that is functionally similar to https://codepen.io/freeCodeCamp/full/VPaoNP

### Instructions
https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-survey-form

## Things I learned
 - Responsive Web Design
   - Starting with a mobile first design will make things faster on mobile
     - Finding break points can be done by increasing viewport size until
         site breaks, either usefully or aesthetically
 - Hiding checkboxes and radio buttons (or custom styling them) in an accessible way
   - leaving it on the page so screen readers can still find them
 - HTML form elements:
   - input
     - text, email, number, radio, checkbox
   - select
     - option
   - textarea
   - form
   - fieldset
 - HTML form element attributes: checked, required, value, name, action, placeholder
 - label
   - nesting form elements inside label
     - is a pain in the butt if you later want to just use the label as a checkbox
       - which could be troublesome from an accessibility standpoint
         - it is bad practice to simply use colours to show different states
   - putting label before or after input elements
   - using *for* attribute to link to form/input element's id
 - More familier with CSS Flexbox

## Goals
 - Become familiar with HTML form elements/tags
 - Use semantic and accesible HTML
 - Make it responsive
 - Use grid and/or flexbox