# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list courtesy of https://leonnoel.com/100devs/

---

## Table of Contents

1. [Behaviorial](#behavioral)
2. [Technical](#technical-questions)
    - [HTML](#html)
    - [CSS](#css)
    - [Javascript](#javascript)
    - [Javascript General](#javascript-general)
    - [Node](#node)
    - [CS Theory](#cs-theory)
3. [Questions to ask your interviewer](#questions-to-ask-your-interviewer)
4. [Whiteboard](#whiteboard)
5. [Resources](#resources)

---

## Behavioral

Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering begin with "At my last opportunity..." or "At my last company". Don't sell yourself out and say "bootcamp" or "school".

### CAR

- **Cause**
  - Why did you need to take action?
- **Action**
  - Steps you took so solve problem
  - Be positive
  - Don't be humble
- **Result**
  - How are you better?

### Questions

- [ ] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time you had to work on several projects at once. How did you handle this?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give an example of an important project goal you reached and how you achieved it.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about yourself.
  - **Cause:**
  I am a person with a background in [background]

I noticed [this problem]

I built [this project]

The resulting success metric was [metric]

This has led me to [your company] where I would love to contribute to [problem company solves]


  - **Action:**
  - **Result:**
- [ ] Tell me about your experience at 100Devs.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you know about our company?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why do you want to work for us?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why are you interested in this opportunity?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your dream job?  What do you really want to do with your career?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me a time when you failed.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you read on a regular basis?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What's some critical feedback you've gotten recently?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Do you have any questions?
  - **Cause:**
  - **Action:**
  - **Result:**

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [ ] What does a doctype do?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you serve a page with content in multiple languages?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What kinds of things must you be wary of when designing or developing for multilingual sites?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are `data-` attributes good for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:**
    gave new features and functionality we have local storage, more semantic tags which helps with accessibility
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe the difference between `<script>, <script async> and <script defer>`.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is progressive rendering?
  - **Explanation:**
 Progressive Rendering is when you render chunks of a webpage in the sever, starting with *critical* content, and stream that to the client in parts so they don't have to wait for a whole page to load.
  - **Use:**
  The use of progressive rendering is to render *critical* content on server while streaming to client, so there is no wait and the page loads faster than client-side-rendering(CSR) and server-side-rendering(SSR). It's also benifitial to users on slower networks. Down-side is it won't be interactive until the page fully loads.

  Used to load *critical* CSS in the head
  - **Example:**
  An exampe of progressive rendering would be Amazon, rendering *critical* content on the server and stream it to the client without waiting after this the non-critical content is streamed to the client
  - **Source:**
  https://medium.com/the-thinkmill/progressive-rendering-the-key-to-faster-web-ebfbbece41a4

- [ ] Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you used different HTML templating languages before?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CSS

- [ ] What is CSS selector specificity and how does it work?
  - **Explanation:**
  CSS selector's specificity uses an algorithm that calculates the weight of a given selector to determine which property value to apply to the element.
  - **Use:**
  Used to determine what propety value is most relevant to apply to a element.
  - **Example:**
  p {..} vs p.class{..} the second seclector weight would be calculated higher because its specificity is higher so the declarations in this would override any of the first selectors declarations
  - **Source:**
  https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity

- [ ] What's the difference between "resetting" and "normalizing" CSS? 
Which would you choose, and why?
  - **Explanation:**
  Resetting CSS is a set of styles that load before your other styles to remove built-in browser styles. 
  Normalizing CSS provides cross-browser consistency in the default styling of HTML elements.

  I would use Normalizing CSS because debugging is easier and it's modular (styling is divided into sections for ease)
  - **Use:**
  The use of Resetting and Normalizing CSS is to make the default in browser to look more consistent across browsers
  - **Example:**
  CSS Reset can force evey browser to have all its styles reset to null
  CSS Normalize will preserve useful default styles rather than stripping all styles
  - **Source:**
  https://www.geeksforgeeks.org/difference-between-resetting-and-normalizing-in-css/


- [ ] Describe floats and how they work.
  - **Explanation:**
  Float is a CSS property that removes an element from the normal flow and places an element on the left or right side of its container.
  - **Use:**
  This could be used to allow text and inline elements to wrap around the floated element
  - **Example:**
  float: left; on an image would remove an element from flow and place it in the top left of its container allowing text to wrap around the element.
  - **Source:**
  https://developer.mozilla.org/en-US/docs/Web/CSS/float


- [ ] Describe z-index and how stacking context is formed.
  - **Explanation:**
  z-index is a CSS property that sets the order of positioned elements that overlap
  overlapping elements with a larger z-index cover those with a smaller one
  - **Use:**
  To overlap elements with a position value (except static) so that it appears closer to you
  - **Example:**
  1{position: absolute; z-index:1;}  2{position:absolute; z-index: 2;}
  2 would overlap 1
  - **Source:**
  https://developer.mozilla.org/en-US/docs/Web/CSS/z-index


- [ ] Describe BFC (Block Formatting Context) and how it works.
  - **Explanation:**
    BFC is a layout concept in CSS to determine the position and size of an element on a webpage
  - **Use:**
  BFC addresses an issue of overlapping/unexpected layout behavior of elements due to HTML default styling
  - **Example:**
  BFC would help contain internal floats and prevent elements from covering each other
  - **Source:**
  https://www.geeksforgeeks.org/explain-the-working-of-the-block-formatting-context/#


- [ ] What are the various clearing techniques and which is appropriate for what context?
  - **Explanation:**
  clear is a CSS property that sets whether an element must be moved below(cleared) of floating elements that come before it.
  - **Use:**
  clear determines which floated element can float beside it and which side it can float. Or if the cleared element uses both then it will be placed below the floats
  - **Example:**
  clear: left; will stop floats from wrapping with the cleared element on its left side.
  - **Source:**
  https://developer.mozilla.org/en-US/docs/Web/CSS/clear?retiredLocale=uk

  
- [ ] Explain CSS sprites, and how you would implement them on a page or site.
  - **Explanation:**
  It's a technique of taking a handful of images and arranging them into one single image
  - **Use:**
  The goal of using an image sprite is to cut down the number of HTTP requests made
  - **Example:**
  Using an image sprite as a background on a span element and then changing the position of the image sprite using background-position property to show different images.
  - **Source:**
  https://learn.shayhowe.com/advanced-html-css/performance-organization/


- [ ] How would you approach fixing browser-specific styling issues?
  - **Explanation:**
  I would approach fixing browser-specific styling issues by using Normalize
  - **Use:**
  Because this makes sure default styles are consistent across different browsers, which can fix many common compatibility issues
  - **Example:**
  - **Source:**
  https://medium.com/@lelianto.eko/how-to-solve-cross-browser-compatibility-issues-with-css-73a4f5083b9e


- [ ] How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:**
  I serve my pages for feature-constrained browsers by the process of building an application for modern browsers while maintaining its functionality in older browsers.
  - **Use:**
  To do this I use feature queries that test if a browser supports a certain feature
  - **Example:**
  /* `@supports` at-rule */
  @supports (color: red) {
   CSS rules to apply
  }

  /* `supports()` function */
    @import `/css/styles.css` supports(color: red);
  - **Source:**
  https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Conditional_Rules/Using_Feature_Queries


- [ ] What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:**
  Using semantically meaningful tags you can create a class like .sr-only to visually hide content meant only for screen readers by positioning the elements off the browser window
  - **Use:**
  Enable better accessibility for users who rely on screen readers
  - **Example:**
  .sr-only {
  position: absolute;
  left: -10000px;
  width: 1px;
  height: 1px;
  top: auto;
  overflow: hidden;
  }
  - **Source:**
  https://medium.com/web-accessibility-tips-tricks-and-techniques-for/web-accessibility-tip-visually-hidden-text-for-screen-readers-a52d954d9711


- [ ] Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:**
  CSS grid layout is great for dividing a page into major parts or defining relationships in size, position, and layer. I would prefer grids over Flexbox when dealing with larger-scale content
  - **Use:**
  allows elements to be aligned into columns and rows
  - **Example:**
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  grid-auto-rows: minmax(100px, auto);
}
.one {
  grid-column: 1 / 3;
  grid-row: 1;
}
.two {
  grid-column: 2 / 4;
  grid-row: 1 / 3;
}
.three {
  grid-column: 1;
  grid-row: 2 / 5;
}
.four {
  grid-column: 3;
  grid-row: 3;
}
.five {
  grid-column: 2;
  grid-row: 4;
}
.six {
  grid-column: 3;
  grid-row: 4;
}
  - **Source:**
  https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout





- [ ] Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**






- [ ] Are you familiar with styling SVG?
  - **Explanation:**
  Yes I have used Scalable Vector Graphics mostly using properties shared between SVG and CSS like font, text, color, and visibility properties.
  - **Use:**
  To manipulate the display of the vector image or the positioning
  - **Example:**
  circle {
  fill: red;
  }
  - **Source:**
  https://css-tricks.com/svg-properties-and-css/


- [ ] Can you give an example of an `@media` property other than screen?
  - **Explanation:**
  Another property of '@media' is print
  - **Use:**
  This is intended for paged material viewed on a screen in print preview mode.
  - **Example:**
  <link rel="stylesheet" media="print" href="print.css">
  @mediaprint(media feature)and(media feature)
  at-rule: media-type: media-feature: operator: mediafeature
  - **Source:**
  https://css-tricks.com/a-complete-guide-to-css-media-queries/


- [ ] What are some of the "gotchas" for writing efficient CSS?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] What are the advantages/disadvantages of using CSS preprocessors?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:**
  
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] How would you implement a web design comp that uses non-standard fonts?
  - **Explanation:**
  Importing that font's src from the web into html and using css font family to set the font and have a backup font style
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] Explain how a browser determines what elements match a CSS selector.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] Describe pseudo-elements and discuss what they are used for.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation:**
  CSS box-sizing property allows us to include the padding and boder in an element's total width and height.
  CSS border-box value calculates width and height of element based on content, padding, and border.
  - **Use:**
  In CSS if using `*` selector with `box-sizing: border-box;` it will calulate width and height for all elements based on content, padding, and border.
  - **Example:**
  *{
    box-sizing: border-box;
  }
  - **Source:**
  https://www.freecodecamp.org/news/what-is-box-sizing-border-box-css/


- [ ] What is the CSS `display` property and can you give a few examples 
of its use?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] What's the difference between `inline` and `inline-block`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Explanation:**
  (sticky)--
  relative - can adjust off box set position but like static
  fixed- positioned to viewport does not leave after scrolling
  absolute - accepts offset stays in flow of doc as long as parent is relative
  static - default of element positioning
  - **Use:**
  - **Example:**
  - **Source:**


- [ ] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

  
- [ ] Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:**
Building a web site to be responsive is when a website responds to the changing window sizes whereas mobile-first is where you start
with the design for mobile and then adjust to growing viewport size.

  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How is responsive design different from adaptive design?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Javascript

- [ ] Explain event delegation
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how `this` works in JavaScript
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how prototypal inheritance works
  - **Explanation:**
  In Prototype Inheritance, an object uses the properties or methods of another object via the Prototype Inheritance
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What do you think of AMD vs CommonJS?
  - **Explanation:**
  Both are used to impllement a module system and commonjs is synchronous and AMD is asynchronys
  CommonJs is going to be easier to work with comming form other languages. 

  Ecmascript is the specification of how JS itself works - the engine - AMD & commonJS are ways/technologies to package/manage dependencies 


  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain why the following doesn't work as an IIFE: `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a closure, and how/why would you use one?
  - **Explanation:**
  The feature of being able to reference a specific instance of a local binding iin an enclosing scope and a function that references bindings from local scopes around it is called closure
  - **Use:**
  This behavior limits concerns of bindings, but also makes it possible to use function values in some creative ways
  - **Example:**
  function multiplier(factor) {
  return number => number * factor;
}

  let twice = multiplier(2);
  console.log(twice(5));
  // → 10

  Thinking about programs like this takes some practice. A good mental  model is to think of function values as containing both the code in  their body and the environment in which they are created. When called,   the function body sees the environment in which it was created, not the   environment in which it is called.

  In the example, multiplier is called and creates an environment in which  its factor parameter is bound to 2. The function value it returns, which   is stored in twice, remembers this environment. So when that is called,   it multiplies its argument by 2.
  - **Source:**
  https://eloquentjavascript.net/3rd_edition/03_functions.html


  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
  https://medium.com/womenintechnology/demystifying-closures-in-javascript-understanding-memory-allocation-and-lexical-scope-13f39db11dc0
- [ ] Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:**
  Both are array methods that itterate over an array. A map array will return a changed array and foreach will be used to view the array without manipulating it
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's a typical use case for anonymous functions?
  - **Explanation:**
    like a helper/throw away function
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between host objects and native objects?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation:**
function Person(){} is a function declaration for creating a constructor function.
var person = Person(); invokes the function immediately, assigning its return value (if any) to person.
var person = new Person(); creates a new instance of Person using the new keyword.
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between `.call()` and `.apply()`?
  - **Explanation:**
    .call passes values .apply can pass values and arrays
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain `Function.prototype.bind`.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] When would you use `document.write()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain Ajax in as much detail as possible.
  - **Explanation:**
    asych js and xml sends data to client without refreshing the page
    having a dynamic website would make it easier to share with others
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the advantages and disadvantages of using Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain "hoisting".
  - **Explanation:**
  when a var declaration looks like it's at the top of its scope
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe event bubbling.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between an "attribute" and a "property"?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:**

  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between document `load` event and document `DOMContentLoaded` event?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the difference between `==` and `===`?
  - **Explanation:**
  `==` performs type coercion before making any comparison, which automatically converts the datatype of one operand to be the same, so comparrison is possible. `===` works like `==` but does not use type coercion, it first checks if datatype matches, then checks value.
  - **Use:**
  `==` for 'loose equality'
  `===` for 'strict equality'
  - **Example:**
  `==`
  const a = 100;
  const b = '100';

  console.log(a == b) // true
  `===`
  const a = 100;
  const b = '100';

  console.log(a === b); // false
  - **Source:**
  https://www.freecodecamp.org/news/loose-vs-strict-equality-in-javascript/

- [ ] Explain the same-origin policy with regards to JavaScript.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5] `
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:**
  Ternary indicates that there is a use of three. The ternary expression is called what it is because the conditional operator takes a condition, a `?` and then a `:`. 
  - **Use:**
  If condition before quesiton mark is truthy it executes code prior to colon if falsy it executes the code after the colon.
  - **Example:**
  function getFee(isMember) {
  return isMember ? '$2.00' : '$10.00';
}
  - **Source:**
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_operator

- [ ] What is "use strict";? what are the advantages and disadvantages to using it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:**
    it dynamically loads so its not seitching to a new page its re rendering the single page?
    using pre render is server side renderer?
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the pros and cons of using Promises instead of callbacks?
  - **Explanation:**
  A situation where callbacks are nested within other callbacks potentially making it difficult to understand and maintin code. You can end up in *callback-hell* Using promises can be a solution to avoid this
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Explanation:**
  typescript locks in the data type so every variablle has a spcific type
  and it can't be changed.

  typescript is typically a little ahead of javascript... because they support transpiling backwards
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What tools and techniques do you use debugging JavaScript code?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What language constructions do you use for iterating over object properties and array items?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the difference between mutable and immutable objects.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the difference between synchronous and asynchronous functions.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is event loop? What is the difference between call stack and task queue?
  - **Explanation:**
  Event loop let's us run code asynchronously. 
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the differences on the usage of foo between `function foo() {}` and `var foo = function() {}`
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the differences between variables created using `let`, `var` or `const`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the differences between ES6 class and ES5 function constructors?
  - **Explanation:**
  difference is syntactical sugar class constructors are easier
  es5 look like standard function but first letter is capitalized and constructor would be seperate
  es6
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What advantage is there for using the arrow syntax for a method in a constructor?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the definition of a higher-order function?
  - **Explanation:**
  takes in a callback 
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example for destructuring an object or an array?
  - **Explanation:**

  - **Use:**
  - **Example:**
  - **Source:**
- [ ] ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
  - **Explanation:**
  It lets us dynamically insert variables into strings without concat
  - **Use:**
  Makes code more resuable and clean
  - **Example:**
  `...${variableName}...`
  - **Source:**
- [ ] Can you give an example of a curry function and why this syntax offers an advantage?
  - **Explanation:**
  transforms the function with multiple arguments into several functions with single arguments.
  - **Use:**
  helps us write modular and reusable code
  - **Example:**
  A funcgion with a large amount of parameters can be turned into a curry function which is the use of nested functions with single arguments.
  - **Source:**
  https://www.geeksforgeeks.org/what-is-currying-function-in-javascript/#
- [ ] What are the benefits of using spread syntax and how is it different from rest syntax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How can you share code between files?
  - **Explanation:**
    export and import modules? modules exports
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why you might want to create static class members?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Javascript General

- [B ] Can you name two programming paradigms important for JavaScript app developers?
  - **Explanation:**
  functional programming and OOP?
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is functional programming?
  - **Explanation:**
    Programming to keep things DRY and SRP
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:**
    Prototypal is used in js because its a prototypal language everything will inherit from the prototype like built in methods. So found in class based languages
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What are the pros and cons of functional programming vs object-oriented programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Node

- [ ] What is Node.js? Where can you use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why use Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the features of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you update NPM to a new version in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is Node.js Single-threaded?
  - **Explanation:**

  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain callback in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is callback hell in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you prevent/fix callback hell?
  - **Explanation:**
  Using Promises or async/await
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the role of REPL in Node.js.
  - **Explanation:**

  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Name the types of API functions in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the functionalities of NPM in Node.js?
  - **Explanation:**
    install packages and dependency managment
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Node.js and Ajax?
  - **Explanation:**
  Completely different things 
  Node works on server side and Ajax works on client side to make asynch calls 
  - **Use:**
  
  - **Example:**
  - **Source:**
- [ ] What are “streams” in Node.js? Explain the different types of streams present in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain chaining in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are Globals in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event-driven programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event loop in Node.js work? And How does it work?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the purpose of `module.exports` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Asynchronous and Non-blocking?
  - **Explanation:**
    doing multiple things at once?
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Tracing in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How will you debug an application in Node.js?
  - **Explanation:**
  Using the debugger that is apart of my environment to insert a breakpoint to watch what values are being held and what 
  returns are being given. Another option is using Chrome DevTools.
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between `setImmediate()` and `setTimeout()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `process.nextTick()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is package.json? What is it used for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is libuv?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the most popular modules of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `EventEmitter` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CS Theory 

- [B ] What is recursion and give an example using javascript?
  - **Explanation:**
  Recursion is when a function calls itself
  - **Use:**
  Recursion can be used instead of a looping variant which describes the concept more clearly. There is a downside however, in JS it's about 3 times slower than the looping version which is generally cheaper than calling a function multiple times.
  - **Example:**
  function power(base, exponent) {
    if (exponent == 0) {
      return 1;
    } else {
      return base * power(base, exponent - 1);
    }
  }

  console.log(power(2, 3));
  // → 8
  - **Source:**
  https://eloquentjavascript.net/3rd_edition/03_functions.html#c_WGJ7JdCP7T


- [B ] What are types?
  - **Explanation:**

  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What are data structures?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is an algorithm?
  - **Explanation:**
    A series of steps to achieve an end goal. Usally optimized to find the best path to the answer.
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is scope / lexical scope in javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is polymorphism?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ B] What is encapsulation?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is a Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is a Doubly Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is a Queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is a Stack?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [B ] What is a Hash Table?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Heap?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Trie?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Binary Search Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Disjoint Set?
  - **Explanation:**
    Apart of data structure sets
  - **Use:**
    In simplified terms, disjoint sets are like LinkedIn or Facebook mutual friends. the disjoint set is used to discover how different friend lists overlap (aka mutual friends)
  - **Example:**
    Not disjointed
    set1 = 1, 2, 3
    set2 = 3, 4, 5
    Is disjointed
    set1 = 1, 2, 3
    set2 = 3, 4
  - **Source:**
- [ ] What is a Bloom Filter?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Bubble Sort and explain when you might use it?
  - **Explanation:**

  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Insertion Sort and explain when you might use it?
  - **Explanation:**
  sorting algorithm that has big o notation of'inserts a value and then sorts
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Merge Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Quicksort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

## Questions to ask your interviewer

1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?
7. If Bob's Burgers hired me today how would you know in a year's time that I was the right fit?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

## Whiteboard

When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time 😉)

- **Parameters**
  - Inputs
  - Ask questions
    - Will it always be a number?
    - Will it ever be negative?
    - Any gotchas?
- **Returns**
  - Ask questions
    - Do you want it returned or is a console.log better?
    - Should I pass a whole array of solutions back or just a single solution?
- **Examples**
  - Show a couple black box examples, aka test cases
    - I pass in these arguments and get these results, is that correct?
  - Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
  - Write pseudocode of each of the steps

## Resources:

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
