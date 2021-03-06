# Testing

## Code Validation
- [W3C Mark-up Validation](https://validator.w3.org/) was used for checking html code for validity and to ensure there were no errors in the html code. 
- [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) was used for checking errors in the CSS code. 

The following links show validation for code, for each html and css file.

1. [index.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/indexvalidation.jpg) show validation.
2. [meetthecats.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/galleryvalidation.jpg), show validation.
3. [menu.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/menuvalidation.jpg) show validation.
4. [contactus.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/contactusvalidation.jpg) show validation.
5. [faq.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/faqvalidation.jpg) show validation.
6. [style.css validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/cssvalidation.jpg) show validation.

## User Story Tests

- As a user, I want an FAQ of the cafe to see which rules to follow while in the cafe.
   * There is an FAQ on the 5th page of the website, where questions and answers can be found regarding the cafe rules. Th link for the FAQ section can be found at the top of the homepage, in the navbar. There is also a link the contact page in case of further questions or queries which is clearly highlighted.
- As a user, I want a menu to see what food/drink are available so I can plan ahead and choose what I want.
   * There is a menu page, with names, descriptions and prices of each food and drink item. This can be accessed via the navbar at the top-right of the homepage. Item names are underlined, with a heavier font-weight to be able to easily identify the different choices of food and drink available.
- As a user, I want a contact/booking section to be able to book times/contact the cafe so I can plan my trip.
   * There is a contact form implemented on the contact page, with different inquiry options in the dropdown list to submit. The dropdown lists various inquiries such as bookings, questions, comments and complaints that can be send via the form. The cafe phone number, e-mail address and location is also clearly visible on this page, allowing the user to plan their trip ahead of time. 
- As a user, I want opening/closing times to see when the cafe is open, so I can prepare my visit in advance.
   * There are opening and closing times in the footer, which is displayed on each of the pages, in a golden colour background with off-white text to clearly highlight the opening and closing times of the cafe. 
- As a user, I want social media links to be able to visit the company’s social media, to see what the company are like.
   * There are social media links in the footer, when hovered over, change color to highlight that the links can be opened. Once opened, the links open in a new tab corresponding to which link was clicked. As the links open in a new tab, it is easy to navigate back to the cafe website without having to use the back button or retyping in the address of the cafe. A user can simply switch tabs and navigate back to the cafe website.
- As a user, I want appealing colours, layout/design of website and a website that is easy to use, to attract me to the website and allows me to navigate the site easily.
   * There is a navbar and links for navigation that are clearly named at the top of each page. This also shrinks down to a hamburger menu in the smaller viewports, which turns into a dropdown list showing links to other pages. The colors were considered carefully and revised after initial building of the homepage. The initial colors used were considered to be boring by a few users who tested the website's overall look and so were changed to a golden color, royal blue, off-white and a chocolate brown for the text in order to make the site more appealing and eye-catching.
- As a user, I want an introduction/info page about the company to see what the company do/what they are about so I can decide if I want to visit the cafe. 
   * The hero text for the homepage includes information about the company, what their aim is and what they do. These are short, but detailed descriptions of what the company does and who they are to give the user a taste of what the cafe is like in a short amount of text so that the user isn't overloaded with information. 
- As a user, I want a map of the cafe to see the location of the cafe so I can prepare my journey in advance.
   * There is a embedded map on the Contact page with a pin, locating the cafe (although the location was randomly selected). The map can be opened up into a large view if needed by the user and the address of the cafe is also listed just above the map on the contact page.

# Responsiveness 

## Index.html 

### Desktop view

In the desktop view, the logo and navbar are in a fixed position at the top of the page. The logo is on the left of the navbar, showing a cat with the words 'Cat Cafe' underneath it to give an immediate hint what the site is showing. The navigation bar has links to the other pages of the website in a row, with the active page's link being highlighted to demonstrate that it is currently active. This spans across the top of the homepage.
The hero image and background span across width of the browser, with a heading and sub-headings with descriptions of the sub-headings. These are centered on the hero image in a large font-size so they are easy to read and catch the user's attention. Underneath the hero image and text, there is a smaller image with the text "ready to book?" and a button, linking to the contact page which has a booking form. The image and button are centered. Next is a carousel of customer reviews. This initially was much larger but it was decided to shrink the size of the carousel so it doesn't fit across almost of the width of the screen. The reviews fade in and out automatically but can also be controlled via the arrows on the left and right of the carousel.
The footer contains the opening times of the cafe, contact information and social media links. On the desktop version, these are in one row but split into three equal columns with plently of spacing between each item to show they are individual items.

### Tablet view 

In the tablet view, the logo and navbar are still at the top of the page with the navbar links being shown. These are spread evenly from the right side of the screen to the left, leaving a margin between the links and the logo image. The navbar again is in a fixed position to allow the user to easily navigate through the website regardless of how far down the page they scroll. 
The hero image has now scaled down to fix the tablet viewport, with the heading, sub-headings and descriptions also scaling down to fit the viewport while still being large enough for the user to read easily. The 'ready to book' image and button are still centralised but also scaled down to be proportionate to the smaller viewport. The carousel also scales down in the tablet view. 
The footer is still separated in three columns and one row but the is less spacing between the columns, however enough to show that they are three separate pieces of information.

### Mobile view 

In the mobile view, the navbar links have now been transformed into a hamburger icon which expands and collapses, showing or hiding the nav links. The logo is still visible on the left of the screen and the position of the logo and navbar is again fixed.
The hero image and text is scaled down to fit the mobile viewport, while being large enough for the user to read easily. The 'ready to book' image now spans across the width of the viewport, however the book button is still centralised and only takes up about one third of the viewport.
The carousel is again scaled down but has margins on either side of the carousel so it doesn't span the whole page. The footer items now stack on top of each other instead of being in the same row, as on the desktop and mobile viewports. 

## Meetthecats.html (Gallery)

### Desktop view

The logo and navbar are displayed at the top of the gallery section, with the nav links all being visible in a row to the right of the navbar. The heading is then displayed below the navbar in a large font-size, which tells the user what the purpose of the page is.
The gallery contains 12 pictures and descriptions of the cafe's cats. Initally, the pictures have no descriptions on them but when an image is hovered over with a cursor, an overlay, description and name of the cat appears over the image. This then disappears/appears as and when the user hovers over an image. There is text just above the first row of photos to hint to the user to hover over the images for a description as user feedback indicated this was not a very obvious action to carry out. Originally, this hint was only incorporated for tablet and mobile viewports but after user feedback, it was also added to the desktop view as well, as users said it was not necessarily an action that would be carried out naturally.
In the desktop viewport, the 12 pictures are split into 4 rows and 3 columns, so that there are 3 photos per row displayed. Each picture has a margin, allowing for there to be some place between each picture so they are more visually appealing to look at, rather than it being too overloading for the user. 
The picture's borders are rounded around the edges just to give it a softer look. The background color remains as the default white, to not take away from the look of the gallery and to not overload the user with too many colors/information as the pictures of the cats are already quite colorful.
The footer is displayed below the images in one row but split in 3 columns as per the index.html. 

### Tablet view

The navbar and logo are still at the top of the page in a fixed position, with all the links being visible in a row. The heading is still visible on the tablet view, but slightly smaller. Above the pictures of the cats, there is again a paragraph to hint that the photos have to be hovered over for the descriptions to show up on the image. 
The images in the tablet viewport now appear in columns of 2 photos per row, instead of 3 per row. This is to allow the size of the images and descriptions to remain relatively large in order to draw the user's interest in. Initially, 9 photos of cats were used in total. This was changed to 12 because with 9 photos, in the tablet viewport, it left one image in its own row at the end of the page and so was unequal to all the other rows with two photos per row. By adding three more photos, this equalled out the rows and looks aesthetically more pleasing.
The footer is beneath the cat images, still in one row with three columns but with less but enough spacing between each secction of information.

### Mobile view

The navbar and logo are scaled down as per the index.html, with the navbar links again being collapsable and expandable via a hamburger menu dropdown. The heading is again visible but has scaled down to the mobile viewport. 
The paragraph to hint to click the image for a description is again visible just above the first image as explained above. The images are now displayed one per row and column so they are stacked on top of one another. Descriptions are still available to view on clicking on an image. 
As there are 12 images to scroll through, the navbar fixed position allows a user to quickly navigate back to the links or desired page with ease. 
The footer information as per the index.html is stacked on top of one another, in the mobile view.

## Menu.html

### Desktop view

The navbar and logo are fixed at the top as per the homepage and gallery. The text for the menu is aligned to the left of the screen in the desktop view, with the background image focus being on the right side of the screen. The is a heading of 'menu' and sub-headings of the different types of drinks/foods available, which is again split into smaller sub-headings with descriptions of the drinks and foods mentioned.
The footer is under the menu and the information is displayed in one row.

### Tablet view

The navbar and logo are such as the desktop view, with the navbar items being visible and selectable. The background image scales down and so the beans on the image carry over a bit to the left side of the screen. The text is still kept to the left side of the screen, with visible headings, sub-headings and descriptions of items sold.
The footer is as per the desktop viewport.

### Mobile view

The navbar and logo scale down to fit the mobile viewport, with the navbar items being expandable and collapsable via a hamburger menu. The heading, sub-headings and descriptions of the items are again listed, but are now more centralised rather than aligned to the left with a margin on both sides of the text.
The footer is also scaled down, with the information columns being stacked on top on another instead of next to each other in a row.

## Contactus.html

### Desktop view 

The navbar and logo are fixed at the top of the page, with the navigation item links being visible in a row. There is a heading of 'Contact Us' at the top of the section. Underneath this, there are contact details for the cafe that are in one row and two columns, with a contact form and map being placed in a row beneath the contact info. The contact form on the left of the screen, has four different fields; Name, E-mail address, Type of Inquiry (with a dropdown list of different types of inquiries) and Comments. The user is unable to submit any information unless the fields are all filled/selected. On the right of the page is the map. This can be enlarged if the user would prefer a larger map. 
Underneath this, there is an image of four kittens with the caption "See you soon" just above it. This image has an off-white background so it blends with the background color of the page so the kittens stand out against the white background. 
The footer is underneath the kittens image, with the information being displayed in one row.

### Tablet view 

The navigation bar and logo are fixed atop the page, with navbar item links being visible in one row. In the tablet viewport, the heading scaled down to fit the screen. The contact information for phone and e-mail text and the contact form are in one column, spanning the width of the screen with a margin on both sides for aesthetics. The contact form again requires information to be in the fields to allow a user to submit. 
Underneath this, the address of the cafe is displayed and the map of the location is underneath the address so that the form and map are stacked in the tablet viewport. 
The kitten image is displayed in another row below the map and form, with the same caption as the desktop view but scaled down to span the width of the viewport.
The footer is at the bottom of the page, with the information being in one row across the viewport. 

### Mobile view 

The logo and navigation bar are scaled down and the navigation item links are in a collapsable/expandable hamburger menu. The heading is scaled own for mobile, The contact information for the cafe and the contact form are also scaled down for the mobile viewport, being stacked on top of one another with a margin between them. The address and location of the cafe are then stacked underneath the contact form, with the map spanning almost the width of the viewport, with a margin. 
The kittens image again is scaled down to fit the viewport, with the 'See you soon!' message displayed as well. The footer section is below the kittens image, with the information being stacked on top of each other instead of in a row. 

## FAQ.html

### Desktop view 

The navigation bar and logo span across the top of the screen, with the navigation item links being displayed in a row next to each other on the right side of the page while the logo is on the left. The navigation bar is in a fixed position for easy navigation. There is a heading of 'FAQ' at the top of the the section. 
In the FAQ section, there are questions and answers displayed. They are stacked on top of one another, with the format of question then answer, question then answer etc. The questions have a semi-transparent background color of a royal blue with off-white text. The answers have a semi-transparent background color of off-white with royal blue text.
The questions and answers are centralised down the page, with margins between them for it to be easier for the user to read the text rather than having the items too close together. The text spans to almost the width of the viewport for longer answers but they do not go beyond a col-10 size on desktop or tablet. The borders of the questions and answers are slightly rounded rather than having a sharp edge. 
The footer is displayed at the bottom of the page, with the information being in one row across the viewport. 

### Tablet view

The navigation bar and logo are displayed at the top of the page, with the navigation item links being in one row to the right of the screen and the logo on the left side of the screen. The 'FAQ' heading is still visible at the top of the section. 
The questions and answers have the same color scheme as the desktop view and they are still stacked, with margins around them to make them stand out and easier to read. 
The footer is displayed at the bottom of hte page, with the information being in one row across the viewport. 

### Mobile view

The navigation bar and the logo are fixed at the top of the page, with the navigation item links being collapsable/expandable with the hamburger menu icon. The hamburger icon is on the right of the page while the logo is on the left. The heading is scaled down for the mobile viewport.
The color scheme remains the same for the mobile viewport and the questions and answers stack on top of one another but the width of the questions and answers span across the mobile view, with a still margin around them. 
The footer section is below this, with the information being stacked on top of each other instead of being displayed in one row, spanning the width of the viewport. 


## Responsiveness in browsers

### [Google Chrome](https://www.google.co.uk/chrome/?brand=CHBD&gclid=EAIaIQobChMIi5nY65OY6gIVKoBQBh15wQBrEAAYASAAEgKlOvD_BwE&gclsrc=aw.ds)

This was the default browser used to build the website in. DevTools was used to check for responsiveness in different viewports as well as inspecting code. With this browser, each page of the website is responsive and acts how it should.

### [Firefox](https://www.mozilla.org/en-GB/firefox/new/)

The website is also responsive on Firefox and there were no bugs found while using the website in Firefox.

### [Microsoft Edge](https://www.microsoft.com/en-us/edge)

The website is responsive in Microsoft Edge, however a bug was found that the semi-transparent background colors for the contact form and the questions and answers failed to display.

### [Safari](https://www.apple.com/uk/safari/) 

The website was responsive and no bugs were found.

## Bugs and resolutions

- On the index.html, there was white space on the right side of the screen on all viewports. 
    * This was resolved by using `html, body{width: 100%; overflow-x: hidden;}` in the css file. 
- Navbar dropdown list items were dropping below the navbar height on mobile and tablet viewports. 
    * Resolved by reducing the padding for list items, creating less space between each item and therefore making it fit on the dropdown menu.
- Home link showing as active item on all pages. 
    *  Resolved by adding the `active` class to the correct element on each page, corresponding to which page is being viewed.
- Unspecific classes were creating bugs on different pages.
    * Made more specific classes fixed these bugs by renaming the classes and then using the new names to make them more specific to what is needed.
- Kittens.jpg image was not responding to smaller viewports. 
    * Resolved by using an `img src` instead of using the image as a `background-image: url`, and adding the class `img-fluid`.
- Vertical line from middle of navbar to bottom was showing. 
    * Resolved by removing the original logo image and turning it into a brand within the navbar.
- Dropdown list for menu was showing on left side of screen. 
    * Moved to right side as wanted by using the `flex` class in Bootstrap.
- A bug was accidentally created by using a 'center' class, to center the text on the readytobook image. Images in the gallery were half cropped due to this. 
    * Resolved by changing the center class name to center-book, making it a more specific class.
- The menu design was originally brown text over a cup of coffee with coffee art on it. It was hard to read brown text over the image in smaller viewports as text was placed over coffee cup. 
    * The background image was then changed to the coffee bean image, with off-white writing and the text being on the left to make it easier to read for users in all viewports.


## Unresolved bugs

- The background image for the FAQ scales down to smaller viewports but doesn't focus on the main coffee cup with the coffee art the smaller the viewport gets. It gets cropped out inside of focusing into the coffee art.
