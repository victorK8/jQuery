## jQuery Course (By Udacity)

### 1. Basics: DOM, $ and Selectors

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
