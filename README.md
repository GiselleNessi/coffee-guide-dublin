# Coffee Guide Ireland
User-Centric Frontend Development - Code Institute

This website is a guide for finding the best specialty coffee in Ireland. It highlights the best specialty cafes throughout Dublin, divided into four regions, and also features two other major Irish cities - Galway and Cork. It aims to help residents and tourists alike to find the best cup of coffee, wherever they are. The project has the potential to expand as the coffee industry in Ireland grows.

## Demo
A live demo can be found [here](https://gisellenessi.github.io/coffee-guide-dublin/).

![Devices Demo](https://github.com/GiselleNessi/coffee-guide-dublin/blob/master/assets/images/coffee-guide-mockup.png "Devices Demo")


## UX

### User Stories

- As a resident of Dublin and coffee lover, I want to have a list of quality coffee shops, so I know where to find the best coffee in my area and elsewhere.

![Cafe list](../assets/images/cafe-list.png "Cafe list")


- As a tourist and coffee lover visiting Ireland, I want to know the exact address of each coffee shop, so I can easily find my way there using Google Maps.

![Google Maps](https://media.giphy.com/media/cmUCLsVkr5hltbZ5cj/giphy.gif "Google Maps")

### Strategy
My goal was to design a simple guide outlining the best speciality coffee shops in Ireland, presenting information in a simple but fun and colourful way.

### Scope
For users, I wanted to provide a useful guide to the best speciality coffee shops in Ireland, featuring essential information and a possibility for users and business owners to feed into future expansion. 
I determined the essentials that users need to be (i) an informative description, (ii) the general area, (iii) the precise location and (iv) a user-friendly site for access while out and about.
A contact form for users or business owners to nominate new cafes to be added to the site may seem out of scope for the average user, but with regular use, users may want to have input into the content on the site.

### Structure
From the home page, I wanted users to be able to select which district of Dublin or Ireland they want to explore, and then produce a list of coffee shops in that location. From the location pages, users can easily access necessary information about each cafe - direct links to the cafe’s website and social media, as well as to the Google Maps location page.
At the bottom of the page users can find the contact form, followed by the footer with our social media links and a brief explanation to remind them what the website is for.

### Skeleton

Home (wireframe)

Cafes (wireframe)

Contact (wireframe)

### Surface

A palette of three high contrast colours was chosen to create a fun but minimal feel. 

## Features

### Existing Features
The navbar uses scrollSpy feature in Bootstrap together with .nav-pills so the user always knows which section of the page they’re at.
The site uses the collapse feature from Bootstrap to show and hide the contact form and cafe details for a more minimal user experience.

### Features Left to Implement
In the future, I would like to add the Google Maps JavaScript API feature to the site, which lets you customise Maps with your own custom content and imagery.
I also plan to add new cafes and locations throughout Ireland, pending user feedback and new cafe openings. 

## Technologies Used

1. HTML5
2. CSS3
3. Bootstrap (4.1.3)
4. JavaScript: Bootstrap uses JavaScript to function; it requires the jQuery and Popper.js libraries
5. Fontawesome.js

## Testing
The website was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 7, X: Chrome and Safari, iPad 10.2”: Chrome and Safari). 

### Home
Every section is highlighted in the navbar as you scroll down the home page. Similarly, by clicking on the links directly from the navbar, the scrollSpy effect will work to bring you to each section.

### Cafes
When you click “View List” from any location in the Cafe section, a new tab opens with the list of cafes grouped by location. Clicking on “More info” under any cafe name shows the cafes details. When open, clicking the button again will collapse the details. 
Clicking on the Google Maps link from desktop opens a new tab with the Maps location, while opening from mobile opens the link directly in the Google Maps app.

### Contact Form
Scrolling to the end of any page will present a “Get in touch” button which, when clicked, will expand the the contact form. Trying to submit the empty form will prompt an alert which advises you to fill out the form. The form will only be submitted if the required fields of contact info and “why” are filled out. Upon successful submission, the page will reload.

## Deployment
The hosting platform for the site is Github Pages, deployed directly from the master branch. You can run the website locally by cloning the repository or using this command in your terminal `git clone https://gisellenessi.github.io/coffee-guide-dublin/`.

## Credits

### Content
The text was taken from each business’s Google description and modified by me for brevity.

### Media
The photos used on this site were obtained from [Unplash](https://unsplash.com/) and [Burst](https://burst.shopify.com/coffee).

### Acknowledgements
I received inspiration for this project from [this Culture Trip article](https://theculturetrip.com/europe/ireland/articles/the-10-best-independent-cafes-in-dublin/).

Navbar components were taken from [here](https://getbootstrap.com/docs/4.0/components/navs/); and modified by me, including by adding an extra feature from bootstrap scrollSpy here.

The two fonts used throughout the site are taken from Google fonts - “Gelasio” for titles and “Libre Franklin” for the rest of the text.

**This site is for educational use.**

