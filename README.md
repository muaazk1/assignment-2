Project Description: The site's purpose is to help university students discover campus activities by serving as a Campus Event Guide. It allows the Office of Student Engagement to inform students about the latest events. The intended audience is North University students. The index.html page of the site is the home page and provides some information about upcoming events and information about the Office of Student Engagement. The event.html page showcases a featured event and recommends other events to attend.

Layout Decisions: I used Flexbox in the header and footer navigation menus, the hero section, and the related events list. Flexbox was appropriate here because these are one dimensional layouts. The navigation menus and hero section lay items along a single row or column and the related events list uses the Flexbox wrapping properties to wrap across multiple rows on narrower screens. I used Grid for the upcoming events grid, and the layout for the main content and sidebar on the featured event page. Grid was appropriate for the upcoming events grid because it required rows and columns to work together as some cards span more than others. Grid was appropriate for the featured event page's main event and sidebar section because the column proportions feature of Grid allowed me to keep the sections sized properly beside eachother in a simpler way than if I were to use Flexbox. 

Responsive Design: The breakpoints I used were 768px and 480px. At 768px, the header navigation switches from right aligned to center aligned, the wide upcoming event cards span 1 column instead of 2 columns, the upcoming events grid goes from 2 columns to 1 and the main content and side bar layout on the featured event page goes from 2 columns to 1 column. At 480px, the button becomes a block level element that is centered, and the height of the card images is reduced to 160px so that they don't take up as much vertical space when stacked. I tested the pages by manually adjusting the viewport window to check the page at each of the breakpoints.

Semantic HTML: I used nav, article, header, and main. I used nav for the navigation menus in the header and footer because these sections are for navigating the site and nav is a better identifier for them than div. I used article for the event cards and the main event content on the featured event page because each of those things represents a piece of content that is self contained. I used header to contain the name of the site, the tagline, and the navigation at the top of each page because it serves as the introductory content of the page. I used main to wrap the main content of each page, because the content within main is unique to each page. 

Sources:

basketball.jpg photo by Markus Spiske on Unsplash https://unsplash.com/photos/ball-under-basketball-ring-BfphcCvhl6E

festival.jpg photo by David Dvořáček on Unsplash https://unsplash.com/photos/a-group-of-people-sitting-on-top-of-a-lush-green-field-3kBIZZluhNc

hero.jpg photo by Priscilla Du Preez 🇨🇦 on Unsplash https://unsplash.com/photos/three-men-laughing-while-looking-in-the-laptop-inside-room-XkKCui44iM0

job-fair.jpg photo by Chidera Faustina Okeke on Unsplash https://unsplash.com/photos/people-signing-documents-at-a-red-table-with-flags-aMNFii9MWUE

mic.jpg photo by israel palacio on Unsplash http://unsplash.com/photos/bokeh-photography-of-condenser-microphone-Y20JJ_ddy9M
 
pizza.jpg photo by Brenna Huff on Unsplash https://unsplash.com/photos/person-picking-sliced-pizza-22Vt7JIf7ZI



