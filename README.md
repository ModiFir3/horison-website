# Code Refactor Starter Code
Link to the original source code: https://github.com/coding-boot-camp/urban-octo-telegram. The Refactor that I have done in detail will be listed beblow in the "commits and edits made in Refactor". To give a quick description of what I have done, I have keep the page to look exactly like the origial source. In order for me to make this website more accessible and up to date with standards I have changed some of the sematics in the HTML for better navigation, added ATL description to the img, and cut down code in the CSS this is just to name a few examples. If you would like to view the website you can here: https://modifir3.github.io/horison-website/

Commits and edits made

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

Content Section
Changed the class of each of the articles in the content section to content-text.
    this reduced the amount of CSS elements needed
        Removed the all CSS connected to old class and merged them to .content-text
        replaced all sources with img to one source .content-text img 
