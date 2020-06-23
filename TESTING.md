## Testing
- [W3C Mark-up Validation](https://validator.w3.org/) This was used for checking html cold for validity and to ensure there were no errors in the html code. 
- [W3C CSS Validation](https://jigsaw.w3.org/css-validator/). This was used for checking errors in the CSS code. 

- [This link](https://i.imgur.com/hGnzN0F.jpg) shows how the html for my website is valid.
- [This image](https://i.imgur.com/GduNbbQ.jpg) shows the CSS for my website is valid.



- I had initial problems with the logo and hamburger menu. They were not responsive to different viewports and the dropdown for the menu had too much padding, making the links drop further below the navbar. By removing extra padding in the CSS this made the dropdown links fit on the navbar instead of falling below. 
- Navbar dropdown list items were dropping below the navbar height on mobile and tablet viewports. Resolved by adjusting the padding for list items.
- Lot of whitespace in smaller viewports between the hero image and readytobook. Bug fixed by applying background-position-y.
- Home link showing as active item on all pages. Resolved by adding 'active' to the correct files, corresponding to which page is being viewed.
- Unspecific classes were creating bugs on different pages - made more specific classes fixed these bugs.
- Kittens.jpg image was not responding to smaller viewports. Resolved by using an img src instead of using the image as a background class, and the class img-fluid.
- Vertical line from middle of navbar to bottom was showing. Resolved by removing the original logo image and turning it into a brand within the navbar.
- Dropdown list for menu was showing on left side of screen. Moved to right side as wanted by using the flex class in Bootstrap.
- A bug was accidentally created by using a 'center' class, to center the text on the readytobook image. Images in the gallery were half cropped due to this. Resolved by changing the center class name to center-book.

### User Story Tests

- As a user, I want an FAQ of the café to see which rules to follow while in the café.
   * There is an FAQ on the 5th page of the website. 
- As a user, I want a menu to see what food/drink are available so I can plan ahead and choose what I want
   * There is a menu page, with names, descriptions and prices of each food and drink item. 
- As a user, I want a contact/booking section to be able to book times/contact the café so I can plan my trip.
   * There is a contact form implemented on the contact page, with different inquiries options in the dropdown list to submit. 
- As a user, I want opening/closing times to see when the café is open, so I can prepare my visit in advance.
   * There are opening and closing times in the footer. 
- As a user, I want social media links to be able to visit the company’s social media, to see what the company are like
   * There are social media links in the footer. 
- As a user, I want appealing colours, layout/design of website and a website that is easy to use, to attract me to the website and allows me to navigate the site easily.
   * There is a navbar and links for navigation that are clearly named. This also shrinks down to a hamburger menu in the smaller viewports. The colors were considered carefully and revised after initial building of the homepage. 
- As a user, I want an introduction/info page about company to see what the company do/what they are about so I can decide if I want to visit the café. 
   * The hero text for the homepage include information about the company, what their aim is and what they do. 
- As a user, I want a map of the café to see the location of the café so I can prepare my journey in advance.
   * There is a embedded map on the Contact page with a pin, locating the café (although the location was randomly selected).


The features were tested on multiple browsers and devices to check if the features were appealing as well as responsive. 