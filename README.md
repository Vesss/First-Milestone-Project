<h2>John Smith's Barbershop</h2>

This project represents a static website for an imaginariy (unexisting) barbershop.
The name "John Smith's Barbershop" was chosen, because John Smith is the most common name in the Anglosphere.

Because John Smith's Barbershop is a men's grooming service, the website uses a retro-looking style.

There is a great emphasis on imagery on the first page - the goal of that is nothing more than a marketing strategy - few text and big, eye-catching images.

UX

The UX is simple. I followed Code Institute's advice of not re-inventing the wheel, so I used Bootstrap (3) to create my project. 
The main colours of the website are black and orange - black being the main colour, but also sitting more on the background. Orange is used for more
particular things, such as buttons.

<h2>FEATURES</h2>

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
the issue.

- Furthermore, the design for a burger button on all devices below large were inspired by another website, which is covered in greater detail
further below in this descriptive document.

<h3>. Heading titles on the home/index page</h3>
- The heading images on the home page, which feature the 3 main services that the barbershop provides, are all clickable links which lead
directly to the prices page, where these same services are again listed in the same order, but with a prices next to the headline and a
description of the service below.

