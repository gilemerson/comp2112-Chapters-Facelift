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


- Change Nav Menus To Different Words Taken From An Array That was Created -



---------------------------------------------------



- Change Logo By Replacing img element, With Our Own Created Element -

let parent = document.querySelector('.indigo-logo');

let oldImg = document.querySelector('img');

let newImg = document.createElement('img');

newImg.src = "http://via.placeholder.com/130x66";

Parent.replaceChild(newImg, oldImg);


---------------------------------------------------


- Using A Template Literal With An Object To Change InnerHTML - 



---------------------------------------------------







