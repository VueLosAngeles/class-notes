## Homework was Section 5 - Understanding the VueJS Instance
+ SPA -  Single Page App
+ PWA - Progressive Web App

proxy - a figure that can be used to represent the value of something in a calculation.

https://codingexplained.com/coding/front-end/vue-js/proxying

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy


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

## Don't use Ref!

### mount
infrequent  
+ https://vuejs.org/v2/api/
+ https://vuejs.org/v2/guide/instance.html
+ https://stackoverflow.com/questions/46831452/difference-between-mount-and-el-vue-js?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa

### template
DON'T USE
```
new Vue {
 el: #app3,
 template: `<h1>`
}
```

### Component Syntax
Vue.component(<name-of-component>, template:`<h1>Jen</h1>`)

Vue.component

### Life Cycle Hooks 
a function that runs within a specific time frame  
Each Vue instance goes through a series of initialization steps when it’s created - for example, it needs to set up data observation, compile the template, mount the instance to the DOM, and update the DOM when data changes. Along the way, it also runs functions called lifecycle hooks, giving users the opportunity to add their own code at specific stages.  

+ Create 
+ Mount 
+ Update 
+ Destroy

+ https://vuejs.org/v2/guide/instance.html#Instance-Lifecycle-Hooks
+ https://alligator.io/vuejs/component-lifecycle/

---


install globally  
github.com/vue/vue-cli

sudo npm install -g @vue/cli

!!

#### @ - part of the npm ecosystem

### command line interface
A command line interface (CLI) is a type of human-computer interface (i.e., a way for humans to interact with computers) that relies solely on textual input and output. That is, the entire display screen, or the currently active portion of it, shows only characters (and no images), and input is usually performed entirely with a keyboard.

The CLI gets its name from the fact that it is an interface which contains command lines. A command line is a space on the display screen in which commands (i.e., instructions telling a computer to do something) are typed in by the user. Pressing the ENTER key after typing in a command causes that command to be passed to the shell. A shell, also referred to as a command interpreter, is a program that provides the CLI as well as reads commands that are typed on a keyboard and then executes (i.e., runs) them. The results of executing many, but not all, commands are also shown on the command line.

CLIs stand in sharp contrast to graphical user interfaces (GUIs), the other main type of human-computer interface. GUIs feature the use of graphic images, including windows, icons and menus. These objects are manipulated by a mouse (and can usually be manipulated to a limited extent by a keyboard as well). 
+ https://en.wikipedia.org/wiki/Command-line_interface  
+ https://www.computerhope.com/jargon/c/commandi.htm  
+ http://www.linfo.org/command_line_interface.html

vue create jenjen
