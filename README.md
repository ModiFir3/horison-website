# Code Refactor Starter Code
Refactor img and broken header
    Spaceing some of the elements for better navigation.
    added the missing <alt> to the <img> and adding a description for each img as well.
    added <id> for search-engine-optimization <div> to connect the <a> in the header

Refactor Header
    html
        changed the begining <div> to <header> semantic
        changed the div surround the <ul> and <li> with a <nav> semantic
        added <strong> to the <a> 
    changes in header CSS
        removed . infront of the header css to work with new semantic
        removed header div ul and combined to header div ul li
        added a margin bottom to bring the img closer to the header
        added bolder font weight to the <nav>

Changed the Semantics of all of the html for better navigation
found more alts to add in the bottom three <img>

Benefits section
    (lead, brand, cost) 
   Changed the class of all the articles in this section to benefit-text.
    This in turn cut down on so many elements in CSS 
        removed .benefits(lead, brand cost) and merged all atributes to .benefits-text 
        removed .benefits(lead, brand, cost) img to one sourse to .benefits-text img  
    added font-size 20px and font-weight to .benefit-text to match the image.
