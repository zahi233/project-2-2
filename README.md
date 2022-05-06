# Reflection

## Concept

The concept I took on was a website that would provide updates for a business location. I chose dinosaur sightings as it is something that can be regularly updated as a blog with images and different semantic elements to show elements such as the date and author of a picture followed by a description. The website appeals to children, so while maintaining the green theme of nature, I used large and legible text and a variety of patterns. 

## Useful parts

The practicality of my design is that upon loading the website you are immediately in front of new content, while at the same time able to see the location of the park through an embedded Google Maps element. The very bottom of the page gives a brief description and history of the park. The grid is set in such a way that navigation for important information is not needed, rather it is all laid out in front of you, with the blog posts on the left and map on the right, and a scroll to the bottom gives the quick "about" info. 

## Coding and designing  

I was stuck for a long time on trying to add images to the static site and at first could only do so through CSS. With CSS I added a background image I found that was dark and blurry so that text in front of it could be read. The hero element was used to boast about the business, and as an Easter Egg for children who may be interested in this place, I used hero:hover to activate a gif in the background of the hero element of waving trees. I did not allude to this with a "hover here" text or anything as when I was younger I was always pleasantly surprised with accidentally coming across little hover activated things like that. 
For mobile view (max 550px), the grid collapses into a single column with the blog content followed by the map. In tablet view and when a desktop window is at a shrunken width (min 551 max 1200px) I made it so that the map is replaced by a much smaller size of itself so that the main content still takes the majority of the width. I did this by creating another google map embed of a smaller size and using display:none and display:block to determine which one shows at what size. 
Before finishing the site I checked my Project 1 CSS file to see if I had missed anything. The left and right side of my grid were too close together but I found the :root {--main-padding: 4px;} in my old CSS fixed that easily. I also used the old CSS to guide my CSS grid. 