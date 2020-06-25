# Gym 24/7 website

Welcome to a Gym website that is easy to navigate, easy to find relevant info and also beautiful.



## Content

* UX
  * Project Goals
  * Users Goals
  * Site Owner Goals
  * User Requirements and Expectations
  * Design Choices
    * Fonts
    * Icons
    * Colours
    * Styling
    * Images
    * Backgrounds

* Wireframes

* Features
  * Features that have been developed
  * Features that will be implemented in the future

* Technologies Used

* Testing

* Bugs

* Deployments

* Credits

## UX

### Project Goals
The goal with the project is to create a website that makes it easier for people to find our (fictional) gym.
The website should be easy to navigate and you should instantly get a good overlook.

#### User Goals

 * Inspire users to try different workout programs and participate in classes
 * Make users to want to workout more
 * The website needs to be user friendly on both desktop, tablet and phone
 
 #### Site Owner Goals
 
  * To attract more customers to our gym
  * To inspire people to be the best version of themselves
  
  ### User Stories
  
  * As a user, I want to be able to get a good overlook right away

  * As a user, I want the website to be easy to navigate

  * As a user, I want the pricing to be straight forward


## User Requirements and Expectations

### Requirements
 * The website needs to be easy to navigate
 * Finding the gyms locations and opening hours should be easy
 * The site needs to be fully responsive
 * The website should be visually appealing 
 * Pricing for the gym membership should be straightforward
 
 ### Expectations
  * The website should have appealing animations
  * There should not be too much information presented at the same time
  * Present information with icons to make it easier to find specific information faster
  
  
 ### Fonts
For this project I'm going to use the Montserrats and font for headings. It's both elegant and eyecatching yet simple. For paragraphs I'm going to use Roboto, Roboto is similar to Montserrat, the two fonts work great together.

Montserrat & Roboto


![Montserrat font](/wireframes/fontscolorsetc/fontmontsserat.png)![Roboto font](/wireframes/fontscolorsetc/fontroboto.png)

[Link to Montserrat](https://fonts.google.com/specimen/Montserrat)

[Link to Roboto](https://fonts.google.com/specimen/Roboto)

### Colours
For the colours I have chosen to go with mainly dark grey and black, I want to keep it elegant. To highlight and keep it intresting I've added red. Red is the color of passion, I think that goes well this specific branding.
![Colors](/wireframes/fontscolorsetc/Colors.png)


### Icons
For the Icons I'm using icons from the fontawesome CDN. The goal here is not to overuse them, keep it simple.

### Styling
For the overall styling of the project I'm using the foundation of Boostrap but on top of that I am using my own styling. 

### Images
The Images goes in the same overall feel and look with the rest of the colorscheme. They are also engaging and happy.
This is the image I've chosen to use for the hero of the website. I used Photoshop to edit the colours a bit.
![Header image](/wireframes/fontscolorsetc/header.png)

All pictures used is from either Pexels or Freepik. Both of these sites are for stockphotos. Every each one will be linked in credits.

### Backgrounds
For the background I'm using the colors I presented earlier. The body background is solid black, so the whole website is dark.

## Wireframes
I used Adobe XD to create the wireframes. Adobe XD is a prototype tool mostly used for creating mockups, wireframes and interactive prototypes. The wireframes I've done are very basic but straightforward. 

### Desktop
You can find the wireframe for the desktop  [here](https://raw.githubusercontent.com/Elinkatalina/Gym-24-7/master/wireframes/desktop.png)

### Tablet 
You can find the wireframe for the tablet [here](https://raw.githubusercontent.com/Elinkatalina/Gym-24-7/master/wireframes/tablet.png)

### Phone
You can find then wireframe for the phone [here](https://raw.githubusercontent.com/Elinkatalina/Gym-24-7/master/wireframes/phone.png)

## Features

### Features that have been developed:
* Jumbotron with navlinks
* Carousell to present different locations
* Navbar collapsing when on smaller screensizes

### Features that will be developed in the future:
* Form to become a gym member

## Technologies Used

### Languages
* HTML
* CSS

### Tools & Libraries
* Boostrap
* Flexbox
* CSS grid
* Adobe XD
* Adope Photoshop
* Adobe Dreamweaver
* Pexels (Stock photos libary)
* FreePik (Stock photos libary)

## Testing
it is important that my site works as planned. So therefore I double test everything to make sure it works as intended.
I test the website by responsiveness and features. I also try to look through the spelling. When I feel like I've gone trought it all I validate the code with the wc3 CSS & HTML validators.

### Header & Navbar
* **Plan:** The header needs to be fully responsive, the header should include a navbar.

* **Implementation:** I used FreePik to find a fitting header image. Then I edited it in Photoshop to fit with the color scheme.
I added the header inside of a Boostrap jumbotron with the navbar. To make it look good on every screen size I changed the size of the image in Photoshop and linked it to the
jumbotron in the different media queries. I link the navlinks to the different sections of the HTML page. The navbar is a Boostrap navbar. It will collapse the navlinks into an icon at smaller screensizes. I customized this for my liking.

* **Test:** I test the responsivness of the header by opening the website in chrome and then resizing the window. I Also doublecheck in the chrome dev-tools, sometimes these two differs, the more correct one is the dev-tools one. I also doublechecked and looked at my website through my phone. I test to see if my nav links works by clicking them. I use the dev-tools to see if my navlinks collapse into my chosen icon properly.

* **Results:** The header work as intended. It is fully responsive on all screensizes. The navbar looks correct and the navlinks properly links to the different HTML-section linked. The navlinks correctly collapse into an icon at smaller sizes.

* **Verdict:** The header & navbar passed all the tests.

### Promocontainer
* **Plan:** The promocontainer should contain text with symbols that promotes the gym and it features. It should display all the icons and text on a single line on larger screens, **two** per line on medium and **one** on each line on smaller screens.

* **Implementation:** I created a container, with a row and 4 columns. In each column I added a header and an icon. I added different col-class so the responsivness would be as intended.

* **Test:** To test that everything is working as inteded, I use the chrome dev-tools to see how the promocontainer responds to different screen sizes.

* **Results:** The promocontainer with the icons and text works as intended, it displays all the icons and text on a single line on desktop, **two** per line on tablet and on desktop it should display all the icons and text on the same line.

* **Verdict:** The promocontainer passed all the tests.

### Picture & text about the gym

* **Plan:** Add a container with a picture of someone workingout or something related to fitness. Add a text within the same container. This text is going to be about the gym from a member perspective. The picture and the text should be presented on a line of it's own on smaller screen sizes.

* **Implementation:** I created a container and within the container i added a row, within the row I added two columns, one for the img and one for the text. For the image I added a class of "img-fluid" so the img would fit nicely inside of the col div. The picture used I found on FreePik. I edited it in Photoshop to match the overall look and feel of the rest of the website.

* **Test:** To see if everything works as intended I once again use the chrome dev-tools to see what it would look like on different screen sizes.

* **Results:** Everything looks and works as expected

* **Verdict:** The picture & text about the gym passed all the tests.

### Class cards

* **Plan:** Add different boostrap cards the represent the gyms different classes. They should have pictures of fitness related things or/and pictures of people working out.
The cards should all be on the same line on big and medium screen sizes. On smaller sizes they should be stacked on top of each other.
I
* **Implementation:** I created a container, within the container a row and within the row I created 3 cols. In every col I added 1 bootstrap card with an image and text. For the images I once again went to FreePik to find my images. I once again used Photoshop to edit them. It took a bit of testing to make sure everything looked good on every screen size. I added spaces between the cards for the smaller screen sizes where the cards are stack. 

* **Test:** To see if everything works as intended I once again use the chrome dev-tools to see what it would look like on different screen sizes.

* **Results:** Everything looks and works as expected.

* **Verdict:** The class cards passed all the tests.





