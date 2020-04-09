## jQuery Course (By Udacity)

### Lesson 1. Basics: DOM, $ and Selectors

#### Introduction

jQuery is a function and a object.

$ == jQuery. $ is a pointer to jQuery function-object.

#### How do I use $?

DOM inspiration like parent tree. Use $ to get DOM elements.

How does $ get DOM elements?

```$('tag')``` by tag

```$('.className')``` by className

```$('#id')``` by id

This methods  return a jQuery Collection. It is an array with some additional methods.


#### How do I move in DOM tree?

``` $('#id').parent() ``` return parent of DOM element.

``` $('#id').parents() ``` return all parents of DOM element.

``` $('#id').children() ``` return children of DOM element.

``` $('#id').siblings() ``` return siblings of DOM element.

``` $('#id').find() ``` return children, grandchildren, etc of DOM element.


### Lesson 2. The tricks: DOM Manipulation

- How to use jQuery API documentation in order to DOM manipulation.
- Use of jQuery functions:

  ```.toggleClass(className)``` to add, remove and toggle class.
  
  ```.next([selector])``` to get next sibling.
  
  ```.attr(attributeName, [value]) ``` to get or set value to attribute
  
  ```.css(propertyname, [value])``` to get or set CSS property/style 
  
  ```.html(String) ``` to get or set html
  
  ```.text()``` to get or set text
  
  ```.remove()``` to remove DOM elements
  
  ```.append()``` to insert DOM elements at the end of list of elements
  
  ```.prepend()``` to  DOM elements at the beginning of list of elements
  
  ```.insertBefore()``` to insert DOM elements before the target element
  
  ```.insertBefore()``` to inset DOM elements after the target element
  
  ```.each(function)``` to apply *function* to an array of DOM elements. Use ```$(this)``` to get current DOM element.
  
  ```$(function)```


### Lesson 3. Event Listeners with jQuery

- What are browser events? Actions that user do during browser navigation. For example, to clik the mouse. Google Chrome Browser has a function ```monitorEvents(ElementToWatch)``` (It doesn`t work in javascript).




### jQuery API Documentation https://api.jquery.com/
