# Srimba-BuildASearchBar
## New Concepts
### keyup
- The keydown and keyup **events** provide a code indicating which key is pressed, while keypress indicates which character was entered. 
### includes()
- The includes() method determines whether an array includes a certain value among its entries, returning true or false as appropriate.

## Other Things that I have learnt
### allNameDOMCollection[counter].textContent
- remember to add textContent
- The textContent property of the Node interface represents the text content of the node and its descendants.

### unknown error
- for me, this occurs when I misspell.
### create a new variable to store along one.
```
let currentName = allNameDOMCollection[counter].textContent.toLowerCase(); 
```       
### event.target.value 
- The addEventListener() method attaches an event handler to the specified element
- addEventListener() has a second parameter of 'function', which gives us an '**event**', which inside has lots of properties and methods
- We can use the property of '**target**' which returns **the element that triggered the event**
- The 'event.target' has another property called 'value', so 'event.target.value' which in the case of our input box, gives us the value the user typed in!

```
let usernameInput=document.getElementById("usernameInput");
usernameInput.addEventListener("keyup", function(event){
    let username=event.target.value
    console.log(username)
})
    
```
### list-style: none
- Adding the "list-style: none" CSS class to the unordered list (`<ul>`) or ordered list (`<ol>`) tag removes any bullet or number.
### document.getElementById    
- Finally! I understand the difference between element and id and why we need to use DOM.
- because id is id and element is element. We could not get element by simply get id.
