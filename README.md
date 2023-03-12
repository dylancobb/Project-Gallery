# Planning
- A large, front-and-center title seems appropriate.
- Maybe something with a gradient?
- The cards contain text columns so I'll probably want two to three cards per row on large screens, and obviously full-width cards in a single column on small screens.
- Cards should probably be structured as nested divs, with classes to style, and IDs to use querySelector() in JavaScript for controlling the text display.
- I like the idea of the cards being simple, similar shades of colour in different hues.
# Building
- I used my standard HTML boilerplate to set up the document, and chose Noto Sans as the sole font for a nice, clean look (with a fall-back of the standard sans-serif).
- SVG code was used for the title to give it a nice gradient fill that will display well in all browsers.
- A subtle off-white ("azure") background colour was chosen.
- I created some thumbnails to use as images for my project cards.
- The nested `<div>` structure of the cards was established with classes for the cards for styling, and IDs for the `<p>` and `<button>` tags for controlling via JavaScript.
- Filled the first two cards with thumbnails, titles and description text.
- Added a script tag at the bottom of the body, and added a couple of lines to set the display of all the `<p>` tags on the page to "none" when the page is loaded.
- Coded a function to take a text and button ID and un-collapse or collapse the text.
- Styled the cards, and the buttons.
- Added a hover effect to the card thumbnails using CSS filters.
# Debugging
- The gradient took a bit of tweaking, as initially it cut off some of the text and I couldn't figure out how to center the title. The solution was setting the width of the element to 100% and controlling the position of the text from inside the SVG code. Not ideal, but since the title is a one-time element on the page, it's not so bad a solution!
- Flexbox controls took a bit of trial-and-error (but less googling than before!)
- Getting the JavaScript function to behave the way I intended took some fiddling. The JavaScript part was fine, but DOM manipulation is still new territory for me 😅
- The hover effect on the card thumbnails was a bit too much, had to tone it down a bit.