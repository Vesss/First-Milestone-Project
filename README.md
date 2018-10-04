<h1>John Smith's Barbershop</h1>

This project represents a static website for an imaginariy (unexisting) barbershop.
The name "John Smith's Barbershop" was chosen, because John Smith is the most common name in the Anglosphere.

Because John Smith's Barbershop is a men's grooming service, the website uses a retro-looking style.

There is a great emphasis on imagery on the first page - the goal of that is nothing more than a marketing strategy - few text and big, eye-catching images.

<h2>UX</h2>

The UX is simple. I followed Code Institute's advice of not re-inventing the wheel, so I used Bootstrap (3) to create my project. 
The main colours of the website are black and orange - black being the main colour, but also sitting more on the background. Orange is used for more
particular things, such as buttons.

<h2>FEATURES</h2>

<h4><i>Existing features</i></h4>

<h3>1. Header Image</h3>

- The website has a retro-shaving image featuring old-school shaving equipment. The header image itself is a link that leads back to the home/index page.
There is a darkening effect upon hovering the image. The image fades out a little - darkening by 25%. This was achieved through a transition.

<h3>2. Navigation</h3>

- The navigation menu is responsive on all devices. Initially the buttons for it were created as columns in a single row, each one taking 2 columns on all devices.
It became a challenge to turn these buttons into a responsive, collapsable burger button smaller devices, which prompted me to use Bootstrap's built-in navigation.
Luckily, not only did it later help in solving the issue of creating the collapsable burger button for smaller devices, but it also provided my website with nicer-looking
buttons.

- The buttons navigation has two horizontal line elements surrounding it on top and bottom. They are outside of the navigation element - 
they are separate elements. The horizontal line elements' purpose is purely cosmetic - the enhance and improve the design.

- The navigation buttons allow the user to go to any of the pages on the website.

- The burger button is hidden on all devices smaller than Bootstrap 3's large (col-lg) breakpoints. Effectively that turns the navigation
into a burger button, which can be expanded upon clicking the burger button, in all devices below 1199px, however I manually made it to collapse
turn into a burger button bellow 1200px, ensuring that I will maintain the buttons visible only on full screen.
The buttons were beginning the shrink unpleasantly on 1199px and were turning into a burger button on 1198px. That one extra pixel solved
the issue. I am coding on a 15.6 inch laptop screen and 15.6 inch screens are standard for many devices, hence why these pixel sizes are used.

- Furthermore, the design for a burger button on all devices below large were inspired by another website, which is covered in greater detail
further below in this descriptive document.

<h3>3. Heading titles on the home/index page</h3>

- The heading images on the home page, which feature the 3 main services that the barbershop provides, are all clickable links which lead
directly to the prices page, where these same services are again listed in the same order, but with a prices next to the headline and a
description of the service below.

<h4><i>Features left to implement</i></h4>

- A back to the top button may be included, although it doesn't seem entirely necessary.
- More interesting and colourful animations for the reponsive burger button could be implemented when my knowledge is expanded with JavaScript. 
- A modal for subscriptions could be added.

<h2>Technologies used</h2>

- Bootstrap 3
- HTML
- CSS
- Cloud9
- Chrome Developer Tools

<h2>Deployment</h2>
The website is deployed via GitHub pages.

Locally it can be run by downloading the files from GitHub and loading them on a coding editor.

<h2>Credits</h2>
- W3Schools
- Stack Overflow

<h3>Content</h3>
- No actual content (in terms of text) has been coppied to my website.

<h3>Media</h3>
- The header image has been obtained from here: https://cdn.shopify.com/s/files/1/0705/2585/articles/Traditional_Shave_Blog_1112x.jpg?v=1507409431
- The black and white barber photo was obtained by Pexels.com - it is a free stock image.
- The straight razor bear shave image is a free stock image: https://media.defense.gov/2014/Jun/11/2000801022/-1/-1/0/140608-M-SV584-074.JPG
- The image of the head shave with a relaxing head massage was taken as a screenshot from a YouTube video - the channel is: ASMR Barber.
- The About Me page image, as well as the 3 small images on Prices page have been downloaded from Google Images with the tools setting turned on to Labeled for Reuse.

<h3>Acknowledgments</h3>
The inspiration for my website came from a British barbershop called 'The Barberhouse Birmingham' They can be found at: https://www.thebarberhousebirmingham.co.uk/.
In particular their previous menu was a design inspiration for my website - the website has now been updated and is no longer featuring it, but it used to collapse to a burger button on medium devices and below.

