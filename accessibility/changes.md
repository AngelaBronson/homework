// Your recommended changes go here

## Visual to the UI (CSS, visual elements)
The following are my suggestions for improving the Provider Search. I also have a few comments regarding what is currently working well within the Provider Search:

-- while it is a good thing that I am able to navigate around the search results window (and change focus) using my keyboard, when I tried to change focus using the arrow keys, nothing happened. It wold be advisable to enable the arrow keys for moving around the page, in addition to the existing ability to move around using the Tab key.
-- I am also not experiencing any change in focus when using the Enter key or Space bar. This could be corrected as well. The only time hitting the Enter key worked was when I typed something into the search box -- then it did show me a list of search results.

-- from a visual standpoint, the whole page is hard to read, due to the light text on a dark blue background. Generally speaking, this lowers readability and should be avoided. It is better to use dark or black text on a light background.
-- the search result boxes themselves do not stand out enough from the dark blue background.  It is actually making my eyes tired to be looking at a page with so many heavy, dark elements. 


## Technical changes: HTML, CSS, Javascript, ARIA attributes
-- the use of suggestive text could be added to enhance the user experience while searching for a drug. A user might not know how to spell the name of a drug or medication, so this would be very helpful to them.
-- also, when I intentionally misspelled the word "ibuprofen", and clicked the "Search" button, it just displayed "No results found". This is a very poor user experience! I would have liked to have seen some results anyway (the search engine could have made a guess as to what I was looking for) OR it could have asked me something like "Did you mean ibuprofen instead?" That way I would have the option to correct my search.

-- the lack of flyout menus (navigation) is a good thing.
-- I saw the padlock at the top of my browser screen and "https" so I know my search is secure. This is good.

## Content
-- more search results could be listed right off the bat, instead of making the user continually click "More -->". 
-- the breadcrumbs at the top are a good touch, but the page that I'm currently on does not stand out much at all (in the top navbar). You could make this a little more evident so the user has a good handle on where they are on the site. 
-- I would have liked to have seen some info on the # of results that were found. Please add something like "Showing 1 to 10 of 28 results".  This way the user can see how many results they would need to look through. 
-- could add a way for the user to print the search results.
-- could add a way to narrow down search results if the user desires.
-- could add a way for the user to easily enlarge the text. 
