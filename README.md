# Reports

Writing everything what I daily do (relating HR) to stimulate myself)
```
 Daily and weekly reports
```
 # December, 24. Sunday.
			  
 Start working: 2 p.m.
 
 * 1. Watching videos http://discover-devtools.codeschool.com with challenges - don't understand anything about DOM. Will try watching some youtube videos (3 p.m.)
 
 * 2. Watching videos on youtube (The Net Ninja) (5 p.m.)
 
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
 
 for JS: (it is not gonna work properly because of (I think) we apply this method on buttons and when we adding new object we can't delete it because page needs to be reload)
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
 
 * 3. Break (6:30 p.m.)
 
 * 4. Event Bubbling (6:45 pm)
 
 ```
 This method is gonna work because it applies on aech element of list in general on list, not on items separately
 
 const list = document.query.Selector('#class ul');
 list.addEventListener('click', function(e) {
   if(e.target.className == 'delete') {
     const li = e.target.parentElement;
     list.removeChild(li)
   }
 })
 ```
 
 * 5. Interacting with Forms (6:45 - begin)
 
 ```
 const = addForm = document.forms['add-book'];
 addForm.addEventListener('submit', function(e) {
   e.preventDefault(); // preventing from default action when tap the button
   const value = addForm.querySelector('input[type="text"]').value // grabbing added text in the input form
   
 })
 ```
 
 * 6. Creating Element (7 pm begin)
 
 ```
 const li = document.createElement('li');
 const = bookName = document.createElement('span');
 const = deleteBtn = document.createElement('span');
 
 //add content
 deleteBtn.textContent = "delete";
 bookName.textContent = value;
 
 //add classes
 bookName.classList.add('name');
 deleteBtn.classList.add('delete');
 
 //append to document
 li.appendChild(bookName);
 li.appendChild(deleteBtn);
 list.appendChild(li); 
 
 ```
 * 7. Custom Search Filter (8 pm begin)
 
 ```
 const searchBar = document.forms['search-books'].querySelector('input');
 searchBar.addEventListener('keyup', function(e) {
   const term = e.target.value.toLowerCase();
   const books = list.getElementByTagName('li');
   Array.from(books).forEach(function(book) {
     const title = book.firstElement.textContent;
     if (title.toLowerCase().indexOf(term) !== -1) {
       book.style.display = 'block';
     } else {
        book.style.display = 'none';
     }
   })
 })
 
 ```
 
* 8. Watched some videos about devtools (not really helpful) (till 9:30 pm)

# December, 25. Monday.

* 1. HR Slides "Closures and Scopes" (1:40pm)

```
  Scopes
  
  Nothing new. Everything is kinda obvious
  Some interesting stuff but nothing important to quote here
  
  Closures
  
  A closure is a function object that retains ongoing access to the variables of the context it was created in (even after the outer function calls it was created within have returned)
  
  Did the Checkpoint in HR learn.makerpass and passed with 3/7 Shocked. Marked underbar as MUST DO again after finishing precourse with paying attention on extra(extra) credit exercises!!!
  
```

* 2. Break (3:30pm) (was very long)
* 3. Made plan for today (a bit of CSS, jQuery and part of Twittler);
* 4. CSS (codeschool.com) (5pm)
      Very basic stuff, noted I need in the end of precourse spend chunk of time for CSS!!!
* 5. jQuery (try.jquery.com) (5.30pm)

```

Will run this code once the DOM is "ready":

jQuery(document).ready(function() {
  <code>
});

jQuery event library
https://api.jquery.com/category/events/

Learned some basic stuff about jQuery - how to use it and where to see info about it. Definitely I need more time to learn it a bit more
```
With billion of breaks finished at 11.30pm


# December, 26. Tuesday.

* 1. Ajax 12pm

```
Asynchronous Javascript And Xml
```


