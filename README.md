# comp2112-Chapters-Facelift
Chapters Facelift (javascript exercise)



Chapter Link
https://www.chapters.indigo.ca/en-ca/books/the-king-the-bowers-files/9780451239785-item.html?ikwid=steven+king&ikwsec=Home&ikwidx=9


- Change The Book Title -

let el = document.querySelector('.title');
undefined
console.log(el.textContent);

                The King: The Bowers Files  
                
el.textContent = "Ice Cream";
"Ice Cream"

---------------------------------------------------


- Change The Book Cover To A Food Picture -

let el = document.getElementById('.product-image__image--single'); 

console.log(el.src); 

el.src = "http://via.placeholder.com/350x150”; 

el.setAttribute(‘title’, 'Gil'); 


---------------------------------------------------


- Change Nav Menus To Different Words Taken From An Array That was Created -  ('.top-nav') *

let words = [‘My', ‘Name', Is', ‘Gil’, ‘Emerson', ‘This', ‘Is', 'My', 'Lab’, 'Two'];

let items Array.from(document.querySelectorAll(‘li'));

Items.map( item, index) => item.textContent = words[index]);


---------------------------------------------------


- Change Logo By Replacing img element, With Our Own Created Element -

let parent = document.querySelector('.indigo-logo');

let oldImg = document.querySelector('img');

let newImg = document.createElement('img');

newImg.src = "http://via.placeholder.com/130x66";

Parent.replaceChild(newImg, oldImg);


---------------------------------------------------


- Using A Template Literal With An Object To Change InnerHTML - 

const name = { ’firstName’ : ‘Gil’, ‘lastName’ : ‘Emerson’};

function render(obj) {

Let snippet = ‘

<ul>
  
<li>${obj.firstName}</li>
<li>${obj.lastName}</li>

</ul>

‘;

Return snippet;

}

let el = document.querySelector('item-price__normal');

El.innerHTML = render(name);

---------------------------------------------------


- Use A Template Literal Within A Template Literal To Create Multiple ul-blocks Above, Using An Array Of Objects, Then Calling The Render(obj) Function By Manually Typing In The Console: -


---------------------------------------------------

- Make The Book's Author Link Go To www.georgiancollege.ca.  -

let el = document.getElementById('.item-contributor__link');

console.log(el.src);

el.src = "http://www.georgiancollege.ca";


---------------------------------------------------


- Make The Button To "Add to Cart" So That It Erases The Body By Adding An AddEventListener('click'...). If you say -




