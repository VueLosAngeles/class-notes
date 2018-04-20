https://gist.github.com/jendiamond/ac7ef0fb43e3505b5515f8dc19b8aa88#file-notes_4-19-18-md

## Homework was Section 5 - Understanding the VueJS Instance
+ SPA -  Single Page App
+ PWA - Progressive Web App

proxy - a figure that can be used to represent the value of something in a calculation.

https://codingexplained.com/coding/front-end/vue-js/proxying

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy

Terminology

handler  
    Placeholder object which contains traps.
traps  
    The methods that provide property access. This is analogous to the concept of traps in operating systems.
target  
    Object which the proxy virtualizes. It is often used as storage backend for the proxy. 
    Invariants (semantics that remain unchanged) regarding object non-extensibility or non-configurable 
    properties are verified against the target. 


$data -   
https://vuejs.org/v2/api/


### Virtual DOM vs Shadow DOM
Vue.js and React both use Virtual DOM so it is a known concept by many but often it is confused with Shadow Dom. ...  

Shadow DOM refers to the ability of the browser to include a subtree of DOM elements into the rendering of a document,  
but not into the main document DOM tree.

https://vuejsfeed.com/blog/learn-the-differences-between-shadow-dom-and-virtual-dom

### getters / setteres
https://en.wikipedia.org/wiki/Mutator_method

anti-pattern - https://www.youtube.com/watch?v=WSgP85kr6eU
https://coderanch.com/t/640403/Getters-Setters-anti-pattern-don

https://vuejs.org/v2/guide/computed.html  
 Computed properties are by default getter-only, but you can also provide a setter when you need it:
 
https://vuejs.org/v2/guide/reactivity.html

https://stackoverflow.com/questions/40871513/using-computed-property-setter-and-getter-to-update-data-properties

https://codeburst.io/vuex-getters-are-great-but-dont-overuse-them-9c946689b414

