# Reports

Writing everything what I daily do (relating HR) to stimulate myself)
```
 Daily and weekly reports
```
 December, 24. Sunday.
			  
 Start working: 2 p.m.
 
 * 1. Watching videos http://discover-devtools.codeschool.com with challenges - don't understand anything about DOM. Will try watching some youtube videos (3 p.m.)
 
 * 2. Watching videos on youtube (The Net Ninja)
 
 ```
 var selector = document.querySelector('#someID');
 
 A lot of stuff I don't understand because I've no idea why do I need it. And because I don't actually use it (only for itself - I mean use it only to see how to use it);
 
 ---Traversing---
 
 .nextSibling / .previousSibling 
 
 .nextElementSibling / .previousElementSibling
 
 .querySelector('p').innerHTML += '<br />Some text!';
 
 ---Events---
 
 Website for all events
 
 https://www.w3schools.com/jsref/dom_obj_event.asp
 
 example from video:
 var h2 = document.querySelector('#id h2')
 h2.addEventListener('click', function(e) {
   console.log(e.target);
   console.log(e);
 })
 
 for JS:
 var btns = document.querySelectorAll('#class .deleteButton');
 Array.from(btns).forEach(function(btn) {
   btn.addEventListener('click', function(e) {
     const li = e.target.parentElement;
     li.parentNode.removeChild(li);
   })
 })
 
 Starting understand why I am learning DOM
 
 This website https://www.w3schools.com/jsref/ is great in general!
 ```
  
