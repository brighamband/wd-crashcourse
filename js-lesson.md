# Intro to Web Dev 2.0 - JavaScript

## Introduce Goal

**** FIXME **** SHOW FINAL PRODUCT THEY'LL BE ABLE TO ACHIEVE AFTER TODAY'S LESSOSN *****

## Lesson

### What is JavaScript?

HTML is the content, CSS is the styling, JS is the interactivity.  JS causes things to happen when users interact with a webpage with their mouse and keyboard.  JS makes things dynamic (not always the same website every time).

### Running JavaScript outside of a Web Browser
- Simple NodeJS demonstration

### Running JavaScript in a Browser
- This is the main way, the way we'll focus on for this tutorial
- Quick demo by opening Dev Tools on google.com - How to Change What Google Looks Like
    - Change Google document title to 'My Website'
    - Refresh and show that changes dissolve
    - Show JS Method: `document.title = 'My Website'` (Once a website is running, we aren't able to explicitly change the HTML, since we can't go in an edit a file for our user while they're using it, but we can use JavaScript to dynamically change HTML, all without reloading the page.)
    - More applicable example, changing to dark mode (`document.querySelector('body').style.background = 'black'`)

### How to use JavaScript on your Website

2 Types:
- Infile JavaScript + Example  (added script tag to bottom of hmtl, js right there)
- Separate File JavaScript + Example (New file for all our js, then we just add `src` with filename to our script tag.  We'll stick to this one, it's industry standard.)

### Ways to trigger JavaScript to run in Web Browser

- On page load (runs entire script not inside of a function
- On events (events are when user interaction happens like clicking or typing, and we can fire functions when they happen)
- - `onClick` method with button (Show example)

### Overview of JavaScript

- Has variables, functions, classes, just like any language

### JavaScript Functions
- `console.log()`
- `console.error()`
- `alert()`
- `confirm()`
- `addEventListener()` - (Show variation example of hooking up button, except by using `addEventListener` instead of `onClick`)

### JavaScript Variables
- `const` (Constant/Final, can't change) & `let` (able to change)
- Possible variable types: 
  - `undefined` (variable declared, but not assigned)
  - `null`  (variable assigned to an empty value)
  - `boolean`
  - `number`
  - `string`
  - `object`
  - `array`

### DOM Manipulation
- `document.title = 'This Website` (Change document title)
- `thisElement.innerHTML = '<h1>Hello</h1>'` (Change element inner HTML contents)
