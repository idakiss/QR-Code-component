# QR-Code-component

First started by creating a new file before using the index.html given to me. From there, I used
style-guide.md as my reference to configure the page; also used multiple references/refreshers from
Mdn docs 

I worked my way up starting from the bottom, the body section; 

Used div, class, id in body, giving the div class 'card' and class for upper and lower; I later got rid of the classes on div and added them to <h1> and <h2> tags

From there, I went up to style tag and added body, card, and 

After that, I moved up to the head tag and added a link tag with a stylesheet and a reference to Google's api font; from there I configured the font by first having to add the weights onto the api url in order to use them in my stylesheet

I had trouble figuring out how to center the image and text and finally got but messed up aligning them from top to bottom. Several hours of trial and error I realized that the tag flex-direction: column; needed to be added to the card class.

I then moved back down to configuring the font. I managed to get the coloring done properly on the first try, but font sizing and their breakpoints did not look the same as they do in the design image given to me as reference. 
Looking at the style-guide.md I'm assuming that the given font size is only for the paragraph "Scan the QR code.." And not for the <h1> and because of this I changed the size on <h1> to match it closer to the design image.
