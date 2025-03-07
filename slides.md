---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /assets/intro.jpg
# some information about your slides (markdown enabled)
title: Software Development | Foundations
info: |
  ## Software Development | Foundations
# apply unocss classes to the current slide
class: text-left
drawings:
  persist: false
transition: slide-left
mdc: true
---

# JavaScript - part 3/8
JavaScript Foundations
- [ ] Code with control flow statements
- [ ] Code iterative statements (`.map` `.filter` `.reduce`)
- [ ] Functions

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
TODO: fill in anchor href above to point to github repo for these slides
- Personal Website assignment due this Sunday midnight EST
-->

---
transition: slide-left
---

# Recap
(15 min) 

- recall operations, expressions, conditionals
- revisit why `null < 40` evaluates to `true`
- revisit debugger when running a function

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
- variables: camelCase, can only use letters $, can't use reserved words
- let a = 'hi'
- function myFn(myVar) {
-     myVar = 'bye'
- }
- myFn(a)
- console.log(a)

- let a = [1, 2, 3]
- function myFn(myVar) {
-     myVar[0] = 0
- }
- myFn(a)
- console.log(a)
-->

---
transition: slide-left
---

# Iterative statements
(50 min) What is a loop? how to write them

It's common for computers to need to do repetitive work

- Demonstrate `for` loops
- Challenge: create a for loop that logs out 'X bottles of beer on the wall' 99 times where X is a number from  99 to 1 
- Challenge: create a for loop that logs out each letter in a given string but uppercased
- Challenge: create a for loop that logs out each letter's character code ([see fromCharCode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCharCode))
- Challenge: create a secret encoder that transposes each letter in a given string to the next letter in the alphabet

<!--
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for
-->

---
layout: image-right
transition: slide-left
image: /assets/traversy.png
backgroundSize: 500px 200px
class: text-left
---

# 10 minute break

🍦 Cool Tips, Trends and Resources:
- ▶️ [map filter reduce image](https://stackoverflow.com/questions/49934992/main-difference-between-map-and-reduce)
- [8 Array Methods](https://www.youtube.com/watch?v=Urwzk6ILvPQ)
- [Array Map in 100 seconds](https://www.youtube.com/watch?v=DC471a9qrU4&pp=ygUZZmlyZXNoaXAgYXJyYXkgZmlsdGVyIDEwMA%3D%3D)
- [Weird History of JavaScript](https://www.youtube.com/watch?v=Sh6lK57Cuk4)
- [100+ JavaScript Concepts](https://www.youtube.com/watch?v=lkIFF4maKMU)

<br>
<hr>
<br>

- 🧪 [Enter anonymous lab questions](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)
- ℹ️ [Course feedback survey](https://circuitstream.typeform.com/to/ZoyYk7px#course_id=SoftwareAN&instructor=9514)

<!-- 
- remember: take attendance
-->

---
transition: slide-left
---

# Other loops `.map` `.filter` `.reduce`
(50 min) 

- Demonstrate `while` `do...while` loops 
- Demonstrate `break` `continue`
- Demonstrate `.forEach` `.map` `.filter` `.reduce` loops (use debugger to see what's happening)
- Challenge: Given an array of trivia questions, output one question as an h1 tag, upon clicking a `<button>`it shows the next trivia question.
- Challenge: Output a given array of cities and filter out cities that begin with the letter 't'
- `['Toronto', 'Vancouver', 'Trenton', 'Montreal']`

<!--
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/forEach
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
- READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
-->


---
transition: slide-left
---

# Exercise
(remainder of time) Practice loops

- Challenge 1: Print Numbers from 1 to 10 using:
   - a `for` loop
   - a `while` loop
   - a `do...while` loop
- Challenge 2: Calculate and print the sum of even numbers from 1 to 20 using:
  - a `for` loop
   - a `while` loop
   - a `do...while` loop
- Challenge 3: Choose a number (ex: 5) and print its multiplication table up to 10
  - a `for` loop
   - a `while` loop
   - a `do...while` loop

<!-- 
READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
-->

---
transition: slide-left
---

## For homework:

- Finish group exercise 
- Continue doing daily JS exercises on [FreeCodeCamp - JS Algorithms & Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/)


<!--
- take attendance
-->
