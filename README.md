The task was to refactor a given webpage to make it meet accessibility standards. Once opened, there were a few things I noticed. First, no alt attributes were present in all 6 of the 'img' elements, 

the 'div class=footer' had an 'h2' heading and did not follow sequential heading order and semantic HTML, 

there were too many 'div' tags; and that made it uneasy on my eyes to read and probably for other viewers as well. Therefore, I implemented semantic HTML elements such as 'header', 'nav', 'section', and 'article' and replaced the non-semantic 'div' elements. 
    
    I could have also used the 'main' element instead of 'section' and therefore 'section' instead of 'article' from lines 36-64, but in my opinion, 'section' and 'article' in this instance works interchangeably. But please let me know if thats the correct way to think about using 'section' and 'article' elements or not!


Using Google Chrome's Dev Tools I was able to play around and adjust the html elements and corresponding css rules (and occasionally break the website) before actually putting my changes on the index.html in VS Code. Using that tool was very essential because it allowed me to correctly transfer changes I made in the browser tab into VS Code without potentially damaging the starting index.html file.