# Milestone Project 1

## Purpose

The purpose of this project is to showcase everything I have learned within the HTML, CSS and User Centric modules of the Code Institute Full Stack Development course. A full list of technologies used can be found in the technologies section of this document.

The purpose of the website for Empire Drives is to promote their business and showcase the services that they offer. The client wants the website to attract more customers and get them to take the first step by requesting a quotation. Please see below for the link to the website.

https://sanjaysanghera.github.io/Milestone-Project-1/
<br>
<br>

## UX

### User Stories

**Who** – Customer.
<br>
**Want** – To view previous work.
<br>
**Why** – So it gives me a better idea of what I want and what kind of service the business offers.
<br>
<br>
**Who** – Customer.
<br>
**Want** – A quick quotation.
<br>
**Why** – To compare prices with other quotes I have received.
<br>
<br>
**Who** – Customer.
<br>
**Want** – To see the pros and cons of each service.
<br>
**Why** – So I know what driveway to go for.
<br>
<br>
**Who** – Customer.
<br>
**Want** – Contact details.
<br>
**Why** – So I can contact the business directly, rather than waiting for them to see my enquiry and contact me.
<br>
### Structure

* All pages will contain a sticky navigation bar at the top. This will become collapsable when on a mobile device. This will also be the only thing that is in the header.
* All pages will contain social media icons and contact information in the footer. On a mobile device only the icons will show.
* All pages will be responsive and the layouts will change according to the screen size.
* The Home page will outline what the business does.
* The Tarmac page will display what a tarmac drive will look like and the pro's of choosing it.
* The Paving page will display what a block paving drive will look like and the pro's of choosing it.
* The Contact page will display the buisness's contact information as well as a form that a customer can fill out to request a quotation.

### Design

#### Colour Scheme
**Light Grey** - Background and navigation links.
<br>
**Yellow** - Page header and hover affect on the navigation links.
<br>
**White** - Section text.
<br>
**Black** - Navigation bar, section text and footer text.
<br>
#### Typography
**Header** - Expletus Sans.
<br>
**Navigation Bar** - Roboto.
<br>
**Main Text** - Roboto.
<br>
#### Wireframes
To see the wireframes for all pages on both desktop and mobile view please click the below link.
<br>
[Wireframes](wireframes/wireframes.pdf)
<br>
<br>

## Features

### Planned Features

**All Pages**
<br>
* The header will contain a navigation bar. This will have 4 links which will direct you to the following pages; Home, Tarmac, Paving & Contact.
* The footer will contain 3 social media icons for Facebook, Instagram & Youtube which will direct you to the website of the icon selected.
* The footer will also have a section of text which will display contact information.
* The mobile view will get rid of the navigation bar and instead have a navigation button. When clicking this button the 4 navigation links will appear vertically on the page. 
<br>

**Home Page**
<br>
* The body will contain the name of the business, Empire Drives. It will also have an image of previous work that has been carried out by the business.
* It will have a section of text which outlines who the business is, what services they offer and what customers had to say about their work. 
* Below the text there will be a "Request A Free Quotation" button which will link to the Contact Page.
<br>

**Tarmac Page**
<br>
* The body will contain the name of the page, Tarmac. It will also have a carousal gallery which will display pictures of a tarmac drive.
* Clicking on the right side of the picture will take you to the next picture, clicking on the left side will take you to the previous picture.
* Below the gallery there will be a section of text explaining the pros of going with a tarmac drive.
<br>

**Paving Page**
<br>
* The body will contain the name of the page, Paving. It will also have a carousal gallery which will display pictures of a paving drive.
* Clicking on the right side of the picture will take you to the next picture, clicking on the left side will take you to the previous picture. 
* Below the gallery there will be a section of text explaining the pros of going with a paving drive.
<br>

**Contact Page**
<br>
* The body will contain the name of the page, Contact. It will have a contact form which will include the following fields; Name. Telephone, Email & Message. 
* The name field will require a text input, the telephone field will require a number input and the email field will require a email input. The message field will be flexible and can have any input.
* All fields will be mandatory to fill out. 
* There will also be a submit button, but this can't be used unless all fields are filled out correctly. If the fields aren't filled out correctly a error message will display when clicking submit. 

### Features Left to Implement

**Review Page**
<br>
The customer would like a page for customer reviews. It will need a review form that the customer will need to fill out to submit their review. This will then need to be checked by the customer before it goes onto the page to prevent any spam. This was not apart of the original plan and will be implemented in the future. 
<br>
<br>

## Technologies Used

* **HTML** - This has been used to structure the project.
* **CSS** - This has been used to style the project.
* **Bootstrap** - This has been used to create the projects main features such as the carousel gallery, quotation button, collapsable navigation bar and contact form.
* **Font Awesome** - This has been used to import Expletus Sans font, Roboto font and the social media icons.
* **GitHub** - This has been used to store and deploy the code for the project.
* **GitPod** - This has been used to create the code for the project.
* **Google Chrome Developer Tools** - This has been used to inspect the web pages and debug any issues.
* **Balsamiq Wireframes** - This has been used to create the wireframes for the project.
<br>


## Testing

Below is all the tests that have been carried out to ensure the website is functioning correctly.
<br>
<br>
**Test that all links are working and go the the correct page.**
<br>
1. Open website in browser.
2. Click on the Tarmac link and ensure it goes to the Tarmac page.
3. Click on the Contact link and ensure it goes to the Contact page.
4. Click on the Home link and ensure it goes to the Home page.
5. Click on the Request A Free Quotation button on the Home Page and ensures it goes to the Contact page.
6. Click on the Facebook icon in the footer and ensure it goes to the home page of Facebook.
7. Click on the Instagram icon in the footer and ensure it goes to the home page of Instagram.
8. Click on the Youtube icon in the footer and ensure it goes to the home page of Youtube.
<br>

**Test that the carousel gallery on the Tarmac and Paving page automatically slides and can change slide with user input.**
<br>
1. Open website in browser and go to the Tarmac page.
2. Wait 10 seconds and ensure the gallery automatically slides to the next picture.
3. Click the left/right arrow and ensure the gallery goes to the previous/next picture.
4. Repeat steps 2 & 3 for the Paving page.
<br>

**Test that the input fields for the contact form are all mandatory.**
<br>
1. Open website in browser and go to the Contact page.
2. In the contact form type in a telephone, email and message.
3. Hit the submit button and ensure an error message pops up asking to fill out the name field.
4. Repeat steps 2 & 3 and ensure all fields are mandatory.
<br>

**Test that the navigation bar is sticky and always stays on the page.**
<br>
1. Open the website in browser.
2. Scroll down the page and ensure the navigation bar is still visible.
3. Repeat step 2 for all pages.
<br>

**Test that the footer always stays at the bottom of the page.**
<br>
1. Open the website in browser.
2. Scroll down the page and ensure that the footer is at the bottom of the screen.
3. Repeat step 2 for all pages.
<br>

**Test that the navigation links and social media icons have a hover effect.**
<br>
1. Open the website in browser.
2. Hover over the navigation links and ensure the colour changes to yellow.
3. Repeat step 2 for the social media icons in the footer.

### Code Validation

* HTML files have been validated using the W3C HTML Validation Service website.
* CSS file has been validated using the W3C CSS Validation Service website.
<br>

## Supported Browsers & Devices

Below is all the browsers and devices the website has been tested on.
<br>
<br>
**Google Chrome (Right clicked the page and selected Inspect then Toggle Device Toolbar)**
<br>
**Microsoft Edge (Right clicked the page and selected Inspect then Toggle Device Emulation)**
* Moto G4
* Galaxy S5
* Pixel 2
* Pixel 2 XL
* iPhone 5/SE
* iPhone 6/7/8
* iPhone 6/7/8 Plus
* iPhone X
* iPad
* iPad Pro
* Surface Duo
* Galaxy Fold
<br>

**Firefox (Right clicked the page and selected Inspect Element then Responsive Design Mode)**
* Galaxy S9/S9+
* iPad
* iPhone 6/7/8
* iPhone 6/7/8 Plus
* iPhone X/XS
* Kindle Fire HDX
<br>

## User Story Screenshots

* [Screenshot of first user story being fulfilled](static/images/userstory1.jpg)
* [Screenshot of second user story being fulfilled](static/images/userstory2.jpg)
* [Screenshot of  third user story being fulfilled](static/images/userstory3.jpg)
* [Screenshot of  fourth user story being fulfilled](static/images/userstory2.jpg)
<br>


## Issues

**Footer would not stay at the bottom**
<br>
To resolve this I made the footer sticky by using code from the first section of the following website.
<br>
https://css-tricks.com/couple-takes-sticky-footer/
<br>
<br>
**Collapsible nav bar links took up too much space on small devices**
<br>
To resolve this I made the nav bar links appear vertical rather than horizontal. 
<br>
<br>
**There was alot of space between the section and footer on larger devices**
<br>
To resolve this I added more text content to the Home, Tarmac and Paving pages.
<br>
<br>
**Carousel gallery was too small on mobile devices**
<br>
To resolve this I increased the width of the gallery in the media query for mobile devices.
<br>
<br>
**Social media icon links were not opening up on a new web page**
<br>
To resolve this I set the rel attribute to noreferrer noopener on all social media icon links.
<br>
<br>
## Deployment

**GitPod Deployment**
<br>
* Open the Milestone-Project-1 repository and click the GitPod button in the top right.
* In the command console type the following and hit enter: python3 -m http.server 3000
* Go to the Open Ports tab next to the command console.
* Click the Open Browser button for port 3000, this will display a preview of the website.
<br>

**GitHub Deployment**
<br>
* Open the Milestone-Project-1 repository.
* Click the "Settings" tab.
* Scroll down to "GitHub Pages" and select the branch as master and the folder as root.
* Save the changes.
* Click on the provided link to go to the published website.
<br>

## Credits

### Content
The text for the Tarmac page was taken from https://www.premiersurfacing.co.uk/hints-tips/the-benefits-of-tarmac-driveways/
<br>
The text for the Paving page was taken from https://www.premiersurfacing.co.uk/hints-tips/5-benefits-block-paving/
<br>

### Media
All images were used from the following sites:
<br>
https://www.pixabay.com
<br>
https://www.pexels.com
<br>
https://www.unsplash.com
  
