# Row Gallery Website 
## Milestone Project 1 - Static Front-End Website

* Row Gallery is a contemporary art gallery located in Dungeness, UK. The aim of the Row Gallery website is to appeal to prospective gallery visitors and clients. The website is designed to be responsive so that it is user-friendly and looks appealing on any device.

* This is my Milestone Project 1 submission for Code Institute's Diploma in Web Application Development course. My website features five pages and is built using technologies that I have learnt including HTML and CSS.

## Live Project

[View the live project here.](https://isabella-mitchell.github.io/milestone-project-one/)

## Repository

[Find the project repository here](https://github.com/Isabella-Mitchell/milestone-project-one)

## Screenshots 

### Home Page Screenshot
<h2 align="center"><img src="assets/readme-images/screenshot-am-I-responsive.jpg"></h2>

### Exhibitions Page Screenshot
<h2 align="center"><img src="assets/readme-images/screenshot-am-I-responsive-exhibitions-1.jpg"></h2>

### Artists Page Screenshot
<h2 align="center"><img src="assets/readme-images/screenshot-am-I-responsive-artists.jpg"></h2>

# Table of Contents 

CONTENTS 

# User Experience (UX)


## User stories

### Prospective Visitors

*These are users considering or already planning a trip to Dungeness and would be interested in visiting the art gallery during their trip.*

* As a prospective visitor I would like to see what is currently on at the art gallery. 
* As a prospective visitor I would like to see when the gallery is open. 
* As a prospective visitor I would like to see information about the art gallery, and why I should pay a visit during my trip. 
* As a prospective visitor I would like to see the art gallery location and how to get there. 
* As a prospective visitor I would like to see what else there is to do near the art gallery.

### Art Collectors 

*These are users who have an interest in the works by the artists represented by the gallery and may wish to buy artworks.*

* As an art collector I would like to see what artists are represented by the gallery. 
* As an art collector I would like to see information about the artists and see examples of their work. 
* As an art collector I would like to see information about the art gallery so that I know they are a respectable and trustworthy organisation. 
* As an art collector I would like to be able to enquire about an artwork for sale. 
* As an art collector I would like to be able to book a consultation either in person or virtually. 

### Business Owners
*These are the owners of the gallery and of the website*

* As the business owner, I want to feel that my business and brand are well represented by my online presence.
* As the business owner, I want my website to be accessible and user-friendly on any device.
* As the business owner, I want my website to feature links to my social media channels.

    
## Design

### Colour Scheme
<h2 align="center"><img src="assets/readme-images/row-gallery-colours.jpg"></h2>

- A simple and refined colour scheme has been used. The pale backgrounds of the website mimic the pale walls of the gallery space, so that the images take centre stage. 

- The footer colour is inkeeping with the palette yet distinguishes this section from the others on the page. 

- I used the [Material Design Colour Tool](https://material.io/resources/color/#!/?view.left=0&view.right=0) to decide on colour choices. 

### Typography

- Headings are in Josefin Sans and normal text is in Lato. Josefin Sans is a striking font which adds character to the website. Lato is a clean and easily readable font frequently used for websites and applications. Sans serif is the fallback font in case the font can not be imported into the site correctly.

### Imagery

- Imagery is very important feature of the website, as the website needs to appeal visually to users and represent the gallery in a good light. 

- The pages feature slightly different image layouts, due to the type of images that need to be displayed. I researched art gallery websites including [Pace Gallery](https://www.pacegallery.com/) and [Arusha Gallery](https://www.arushagallery.com/) to see the types of content that they typically display on their websites. I incorporated the following into my website:
    - Image Slideshows in landscape orientation on the Exhibition Page
    - Image captions on the Exhibitions Page
    - Artist Portraits on the Artist page

- Consistant aspect ratios have been used to bring a harmony to the site across different page layouts.
    - An aspect ratio of 16:9 has been used for the lead images on the Exhibition Page and Artist Page  
    - An aspect ratio of 3:2 has been used for the Homepage section images and the About Page images
    - An aspect ratio of 2:3 has been used for the Artist Page portraits.
    - A near-square aspect ratio has been used on the Exhibition Page for images that do not suit the aspect ratio of the Image Carousel.

### Icons
- I used icons from Font Awesome to encourage users to click on buttons and to add clear visual indicators to sections on the About page.

## Structure
### Information Architecture
- The website has a Homepage, and then 4 further pages; Exhibitions, Artists, About and Contact.
    - Homepage - Landing page with brief descriptions and links out to the other pages.
    - Exhibitions - Provides information (images and text) about 2 exhibitions
    - Artists - Proivdes information (images and text) about 5 artists
    - About - Provides information about the gallery plus visiting information including a map and directions
    - Contact - Provides a contact form
- Most pages feature buttons with 'call to actions' and internal links where appropriate, quickly directing them to relevant information on another page. For example, you can access the About page for visiting information from the Exhibitions page. This saves repeating information, and helps keep the website clean and consise.
- I decided  to keep long scroll pages rather than introduce further landing pages to reduce number of clicks the user needs to make to find information.

### Navigation Bar
- Each page is featured the nav bar, allowing the user to easily navigate between them without needing to go back to the homepage.
- The Naviagtion bar appears as a horizontal list on desktop, and a vertical drop down menu on mobile.
- The Nav bar is not sticky, this means that the user can see more images and text on their screen.
- I have used the Bootstrap Navigation componant. I have overridden the default opacity because, when I tested the website using Chrome Lighthouse, the colour contrast was deemed insufficient.
- For this reason, I have also added an underline to the 'active' page and to the hover state of non-active pages.

<h2 align="center"><img src="assets/readme-images/design-nav-bar.jpg"></h2>
<h2 align="center"><img src="assets/readme-images/design-nav-bar-mobile.jpg"></h2>

### Back To Top Button
- Pages with a lot of content feature a 'Back To Top' button. This appears at the bottom of the page on smaller device sizes, and saves user needing to scroll back up to the Navigation Bar.
- The button features an 'up' arrow, to make it clear that it will quickly send users back to the top of the page.
<h2 align="center"><img src="assets/readme-images/design-back-to-top-mobile.jpg"></h2>

### Buttons/ CTA
- Buttons are consistent in design across the site. The colour of the button depends on the background colour.
- Buttons feature a right arrow to encourage them to click and be taken to a new page.
- Buttons change colour on hover state. The button text is legible both in its normal and hover state.
- I have used a Bootstrap Button class
<h2 align="center"><img src="assets/readme-images/buttons-dark.jpg"></h2>
<h2 align="center"><img src="assets/readme-images/buttons-light.jpg"></h2>

### Page Heading & Sub Navigations.
- All pages other than the homepage feature a Page Heading.
- The Exhibitions, Artists and About pages feature a sub-navigation. These use ID names to allow website users to quickly jump to content.
- This means that users can quickly find the section they are looking for, without needing to click through another page.
- An underline appears underneath a link when it is hovered over. This further emphasises that this is a clickable link, and mirrors the behaviour of the main navigation bar.
- Aria-Labels have been used to make their purpose clear to Screen Readers.
<h2 align="center"><img src="assets/readme-images/design-page-header-highlight.jpg"></h2>

### Footer
- The Footer includes the Gallery's address, phone number,email address and social media links.
- The phone number and email address are tel: and mailto: links respectivaly.
- Social Media links open in a new page.
- The Footer remains consistant on each page.
- The social media links code was originally sourced from Code Institute's Bootstrap CV project.
<h2 align="center"><img src="assets/readme-images/design-footer-desktop.jpg"></h2>
<h2 align="center"><img src="assets/readme-images/design-footer-mobile.jpg"></h2>

## Wireframes
- [View my wireframes in PDF form here.](wireframes/wireframes.pdf)

# Features

## Current Features

### Responsive on all device sizes
- Through using mobile first design I have created a website that is fully responsive on all screen sizes.
- I have used the Bootstrap grid system and Flex classes to adjust the layout based the device screen size. This allows the images and texts to look good and be easy to read.

### Interactive elements
- Videos on the Artists Page feature controls so that the user can choose to play and pause them.
- Image Caroseuls on the Exhibitions Page feature forward and back buttons that the user can use to control the images. It also includes an indicator so the user can see what slide they are on.
- Google map iframe on the About Page show users the location of the hotel.
- The Nav bar turns into a drop down navbar on smaller devices.
- CSS transitions have been used on the nav bar, page sub-navigations, buttons and social media icons.

## Future Features

### Events
- There could be an events section with a booking form, allowing users to book tickets for upcoming events.

### Past Exhibitions
- There could be an archive of past exhibitions

### E-Commerce
- There could be an online shop allowing users to buy art online.

## Technologies Used

### Languages Used.

- [HTML5](https://en.wikipedia.org/wiki/HTML5)

- [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks Libraries and Programs

- [Bootstrap 4](https://getbootstrap.com/) 
  - I used bootstrap throughout the site to make it responsive. The website uses Bootstrap's Containers, Grid System and Flexbox. I sourced code from the Bootstrap documentation when building the Nav bar, Carousel, Buttons and Contact Form, 
  
- [Google Fonts](https://fonts.google.com/)
  - Two fonts were imported from google fonts. Josefin Sans for the headings, and Lato for the other text.
  
- [Font awesome](https://fontawesome.com/)
  - I used icons from font awesome to visually distinguish sections of the text and on buttons.

- [Git](https://git-scm.com/)
  - Git was used as a version control in the terminal.

- [Github](https://github.com/)
  - Github was used to create and store the project repository.

- [Gitpod](https://gitpod.io/)
  - Gitpod was used to create my files and where I wrote the code.

- [jQuery](https://jquery.com/)
  - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.

- [Balsamiq](https://balsamiq.com/)
  - Balsamiq was used to create Wireframes for the project during the initial planning stage.

- [Am I responsive](http://ami.responsivedesign.is/)
  - Am i responsive was used to take screenshots of the page at different screen sizes.

ADD MORE

## Testing

## Deployment

## Credits

Notes coding 22/03/22 - 22/03/22

Spent a while picking fonts - still not convinced on Lato
Still to confirm secondary colour - 
Spent a while doing layout - to look more into flex - bugs like making things go to right
Stacking guide -  https://bootstrapcreative.com/bootstrap-push-pull-column-ordering-tutorial
Edit images first - makes life easier
reffered to oslo hotel project
media queries to make text center on mobile

Tool used: https://www.softr.io/tools/svg-wave-generator
Bootcamp documentation

Bugs
Images to fit in div - ended up giving up on relative/ absolute - I was confusing myself
Nav - get to stick right
adding justify-right to right hand image
Added padding to section-row, make spacing fit better.

Changes in design
Might keep copy high - as suggested by mentor.
Was looking for CSS shapes - found the wave tool and used a SVG

25.03

Added Footer
Made buttons
Improved homepage code
Picked images
Fewer bugs :)
Created exhibiton page

Added in hr header + footer colour - better ux

check heading/ h2/ h1 on page

change class names 'home'
make better button rules

Completed Froggy flex - https://flexboxfroggy.com/
bootstrap docs

27.03.22

Made artists page - contined updating spacing/ added containers

28.03

Made visit and started about page 

To do
finish about page
make contact page
neaten code
Fill with content.

Bugs
Nav move - resolved - something to do with scroll bar appearing/ not appearing.
Buttons not flush
How to get here spacing
check all divs and indentation
buttons as links


31.03.

Contact page
Fixed jumbatron


Questions
Video
Slideshow
UX
Using bootstrap classes/ css