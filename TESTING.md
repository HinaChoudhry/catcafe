# Testing

## Technologies used for testing
- [W3C Mark-up Validation](https://validator.w3.org/) was used for checking html code for validity and to ensure there were no errors in the html code. 
- [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) was used for checking errors in the CSS code. 

### Validation of code

The following links show validation for code, for each html and css file.

1. [index.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/indexvalidation.jpg) show validation.
2. [meetthecats.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/galleryvalidation.jpg), show validation.
3. [menu.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/menuvalidation.jpg) show validation.
4. [contactus.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/contactusvalidation.jpg) show validation.
5. [faq.html validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/faqvalidation.jpg) show validation.
6. [style.css validation results](https://github.com/HinaChoudhry/catcafe/blob/master/readmeimages/cssvalidation.jpg) show validation.

## User Story Tests

- As a user, I want an FAQ of the café to see which rules to follow while in the café.
   * There is an FAQ on the 5th page of the website, where questions and answers can be found regarding the cafe rules. This can be found at the top of the homepage, in the navbar. There is also a link the contact page in case of further questions or queries which is clearly highlighted.
- As a user, I want a menu to see what food/drink are available so I can plan ahead and choose what I want.
   * There is a menu page, with names, descriptions and prices of each food and drink item. This can be accessed via the navbar at the top-right of the homepage. Item names are underlined, with a heavier font-weight to be able to easily identify the different choices of food and drink available.
- As a user, I want a contact/booking section to be able to book times/contact the café so I can plan my trip.
   * There is a contact form implemented on the contact page, with different inquiries options in the dropdown list to submit. The dropdown lists various inquiries such as bookings, questions, comments and complaints that can be send via the form. The cafe phone number, e-mail address and location is also clearly visible on this page, allowing the user to plan their trip ahead of time. 
- As a user, I want opening/closing times to see when the café is open, so I can prepare my visit in advance.
   * There are opening and closing times in the footer, which is displayed on each of the pages, in a golden colour background with off-white text to clearly highlight the opening and closing times of the cafe. 
- As a user, I want social media links to be able to visit the company’s social media, to see what the company are like.
   * There are social media links in the footer, when hovered over, change color to highlight that the links can be opened. Once opened, the links open in a new tab corresponding to which link was clicked. As the links open in a new tab, it is easy to navigate back to the cafe website without having to use the back button or retyping in the address of the cafe. A user can simply which tabs and navigate back to the cafe website.
- As a user, I want appealing colours, layout/design of website and a website that is easy to use, to attract me to the website and allows me to navigate the site easily.
   * There is a navbar and links for navigation that are clearly named at the top of each page. This also shrinks down to a hamburger menu in the smaller viewports, which turns into a dropdown list showing links to other pages. The colors were considered carefully and revised after initial building of the homepage. The initial colors used were considered to be boring by a few users who tested the website's overlook look and so were changed to a golden color, off-white and a chocolate brown for the text in order to make the site more appealing and eye-catching.
- As a user, I want an introduction/info page about company to see what the company do/what they are about so I can decide if I want to visit the café. 
   * The hero text for the homepage include information about the company, what their aim is and what they do. These are short, but detailed descriptions of what the company does and who they are to give the user a taste of what the cafe is like in a short amount of text so that the user isn't overloaded with information. 
- As a user, I want a map of the café to see the location of the café so I can prepare my journey in advance.
   * There is a embedded map on the Contact page with a pin, locating the café (although the location was randomly selected). The map can be opened up into a large view if needed by the user and the address of the cafe is also listed just above the map on the contact page.

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

The logo and navbar are displayed at the top of the gallery section, with the nav links all being visible in a row to the right of the navbar. The heading is then displayed between the navbar in a large font-size, which tells the user what the purpose of the page is.
The gallery contains 12 pictures and descriptions of the cafe's cats. Initally, the pictures have no descriptions on them but when an image is hovered over a description and name of the cat appears. This then disappears/appears as and when the user hovers over an image. 
In the desktop viewport, the 12 pictures are split into 3 rows and 4 columns, so that there are 3 photos per row displayed. Each picture has a margin, allowing for there to be some place between each picture so they are more visually appealing to look at, rather than it being too overloading for the user. 
The picture's borders are rounded around the edges just to give it a softer look. The background color remains as the default white, to not take away from the look of the gallery and to not overload the user with too many colors/information as the pictures of the cats are already quite colorful.
The footer is displayed below the images in one row but split in 3 columns as per the index.html. 

### Tablet view

The navbar and logo are still at the top of the page in a fixed position, with all the links being visible in a row. Above the pictures of the cats, there is now a paragraph to hint that the photos have to be clicked for the descriptions to show up on the image. This was added for tablet and mobile viewports as the user is unable to hover as they would on a desktop with a cursor. The likeliness of a user hovering over an image with a cursor on desktop is high and so the descriptions would show. After testing by users on tablet and mobile, feedback was that a hint is needed to click the photos on tablet and mobile viewports due to the unlikeliness of a user clicking a picture 'by accident'. 
The images in the tablet viewport now appear in columns of 2 photos per row, instead of 3 per row. This is to allow the size of the images and descriptions to remain relatively large in order to draw the user's interest in. Initially, 9 photos of cats were used in total. This was changed to 12 because with 9 photos, in the tablet viewport, it left one image in its own row at the end of the page and so was unequal to all the other rows with two photos per row. By adding three more photos, this equalled out the rows and looks aesthetically more pleasing.
The footer is beneath the cat images, still in one row with three columns but with less but enough spacing between each secction of information.

### Mobile view

The navbar and logo are scaled down as per the index.html, with the navbar links again being collapsable and expandable via a hamburger menu dropdown. 
The paragraph to hint to click the image for a description is again visible just above the first image as explained above. The images are now displayed one per row and column so they are stacked on top of one another. Descriptions are still available to view on clicking on an image. 
As there are 12 images to scroll through, the navbar fixed position allows a user to quickly navigate back to the links or desired page with ease. 
The footer information as per the index.html is stacked on top of one another, in the mobile view.




The features were tested on multiple browsers and devices to check if the features were appealing as well as responsive. 
- I had initial problems with the logo and hamburger menu. They were not responsive to different viewports and the dropdown for the menu had too much padding, making the links drop further below the navbar. By removing extra padding in the CSS this made the dropdown links fit on the navbar instead of falling below. 
- Navbar dropdown list items were dropping below the navbar height on mobile and tablet viewports. Resolved by adjusting the padding for list items.
- Lot of whitespace in smaller viewports between the hero image and readytobook. Bug fixed by applying background-position-y.
- Home link showing as active item on all pages. Resolved by adding 'active' to the correct files, corresponding to which page is being viewed.
- Unspecific classes were creating bugs on different pages - made more specific classes fixed these bugs.
- Kittens.jpg image was not responding to smaller viewports. Resolved by using an img src instead of using the image as a background class, and the class img-fluid.
- Vertical line from middle of navbar to bottom was showing. Resolved by removing the original logo image and turning it into a brand within the navbar.
- Dropdown list for menu was showing on left side of screen. Moved to right side as wanted by using the flex class in Bootstrap.
- A bug was accidentally created by using a 'center' class, to center the text on the readytobook image. Images in the gallery were half cropped due to this. Resolved by changing the center class name to center-book.