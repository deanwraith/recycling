# Recycling! https://deanwraith.github.io/recycling/

The Recycling! website was inspired by my current job. I work as a grade 3 teacher and the children are working on a unit covering Sustainability and sharing the planet. We are specifically focusing on recycling and all the different ways they can get involved and make a difference. This website will explain different aspects of recycling and give the users tips and additional resources to help them recycle more efficiently.

The website will focus on the 3 R's; Reuse, Reduce and Recycle, and explain how important each one is and give some helpful information on how to go about implementing this in your everyday life. The information in the website will be simple to follow and include educational resources that all ages can learn from and understand.

## Table of Contents

<ol>
<li>
Features
<ol>
<li>Balsamiq Mock Ups</li>
<li>Existing Features</li>
<li>Features to be added</li>
</ol>
</li>
<li>
Testing
<ol>
<li>Validation Testing</li>
</ol>
</li>
<li>Developement Cycle</li>
<li>Deployment</li>
<li>Credits</li>
</ol>

## 1.Features

### 1.1 Balsamiq Mock Ups
[Balsamiq](https://balsamiq.cloud/s1tadm0/p9i349d)

### 1.2 Existing Features
* Navigation Bar
    * The navigation bar will be the same across all the pages on the website. It will contain the title of the site and a drop menu allowing easy navigation between the various pages.
    * The pages that will be accessable from the drop down menu will be Home, Reuse, Reduce, Recycle and FAQ/Send us a question.
    * By having the same navigation bar on all pages allows ease of use and a simple way for the user to find the page they are looking for.

![Navigation bar with no menu](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/nav%20bar%20no%20menu.jpg)

![Navigation bar with menu open](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/nav%20bar%20with%20menu.jpg)

* Home Page Images
    * The home page will consist of a hero image that will extend the width of the page catch the users attention.
    * There will also be a inspirational quote that will be under the images to help in inspiring the user to start using these concepts.

![Cover image of children picking up trash and inspirational quote](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/cover%20image%20and%20quote.png)
    
* 3R's Section
    * The 3R’s section will give the user a visual break down of the best way to live more sustainably and environmentally friendly. There will be a color and text distinction for each section.
    * Each block section will have a flip functionality that when flipped by hovering the mouse over the card there will be additional information on the back.

![Summary section for Reuse, Reduse and Recycle no flip](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/summary%20section%20no%20flip.jpg)

![Summary section for Reuse, Reduse and Recycle with flip](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/summary%20section%20with%20flip.jpg)

* The Footer
    * The footer will include links to various social media sites.

![Footer containing social media links](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/footer.png)


* Reuse, Reduce and Recycle
    * Each of the concepts will have a page that has images and video resources with text descriptions and helpful tips on how to implement them in your everyday life.
    * All three pages will have the same format and structure for ease of use and visual comfort. The pages will also have the same header and footer structure as the rest of the site.

![Reuse page](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/reuse%20page.png)

![Reduce page](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/reudce%20page.png)

![Recycle page](https://github.com/deanwraith/recycling/blob/master/assets/images/recycle%20page.jpg)

* Q&A/Ask a question Page
    * This page will have some frequently asked questions with the answers and a form where any other questions can be sent in and answered.

![Question form](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/faq%20form.png)

![FAQ section](https://github.com/deanwraith/recycling/blob/master/assets/images/readme-images/faq%20questions.png)

### 1.3 Features to be Added
*Features can be discussed and added*

## 2. Testing
Testing of the site was done through the whole development of the site checking as a new feature or style was added on how that effected the specific pages and the functionality.

* Logo functionality - When the logo is clicked it will take you back to the home page. **Tested and passed**.
* Menu icon - When hovered over with cursor the menu dropsdown to display available pages. These can be clicked and will take you to the respective pages. In the dropdown the current page will be underlined and the page the cursor runs over will be underlined. **Tested and passed**
* Reuse, Reduce and Recycle cards - When hovered over with the mouse cursor the card will flip to display more information about the section. **Tested and passed**
* Footer - In the footer it contains 4 social media icons that link to the respective social media page. **Tested and passed**
* Reuse, Reduce and Recycle pages - There are 4 sections per page with the bottom right section containing a video. The video does not play automatically but starts once clicked. **Tested and passed**
* Header and footer - Function the same on all pages. **Tested and passed**
* Hover function on menu and flip cards for mobile changes to click function. Menu does not close on click.

Responsiveness testing was done using several mobile devices of different size to see the site effectiveness at different resolutions. 
The devices used were:
* Iphone SE
* IPad
* HP Elite Book Laptop as well as the Inspect function on Google Chrome Browser to test most resolutions and devices.

### 2.1 Validation Testing
* HTML
    * W3C Validator
    All HTML code was checked using this validator and was returned without any issues.
* CSS
    * Jigsaw Validator
    All css code was tested using this validator and was returned with no issues.

### 2.2 Unfixed Bugs
* I found a bug while using mobile devices where the hover setting for the dropdown menu changed to a click and drop function by default but the menu stayed open once clicked on that page even if the menu icon was clicked again.

## 3. Developement Cycle
* Commit Diary
    * 11:22 23/05/2021 - Initial Commit
    Added boiler plate HTML and assets folder which includes the style.css file and a folder for media resources to be added at a later stage.
    * 11:44 23/05/2021 - Heading Style and Content
    Added content and styling to the header element with the basis for the menu to be adjusted at a later stage into a dropdown menu.
    * 12:21 23/05/2021 - Dropdown Button and Styling
    Added dropdown button functionality and styling.
    * 13:59 23/05/2021 - Dropdown Button and Styling
    Dropdown button moved to right of page! Finally! Really struggled with this.
    * 10:28 24/05/2021 - Header and dropdown
    Changed the header and dropdown button functionality and styling by using w3.css.
    * 24/05/2021 - Header and dropdown
    Removed the w3.css style templates and added my own code for the header and dropdown menu. Added styling and functionality to the header and dropdown menu.
    * 25/05/2021 - Main Image and Quote text
    Added the main image and quote text and added styling to both elements.
    * 25/05/2021 - Summary Section
    Added content and styling to the summary section.
    * 27/05/2021 - Styling and functionality
    Added styling to the summary section for the concepts. Fixed general styling and functionality for the header and dropdown button. Added footer with content. Added pages for concepts and styled them, used Flexbox which turned out to be great!
    * 27/05/2021 - Pages
    Added structure and functionality for additional pages. Followed with content and styling.
    * 30/05/2021 - Pages and Media Queries
    Added and adjusted content and functionality for Reuse, Reduce and Recycling pages. Changed the structure and styling of the summary section on the home page. Added content and functionality to the FAQ including a form to send questions.
    * 08/06/2021 - Adjusted padding and margins
    Added styling adjustments to logo, menu, quote and text on Reuse/Reduce and Recycle pages. Adjusted padding and margins for these elements.
    * 10/06/2021 - Added styling to 3R's section
    Added new functionality and styling to the 3R's description section. Also added responsiveness for this new section.

## 4. Deployment

* The site has been deployed using Github Pages.
    * The site can be found at https://deanwraith.github.io/recycling/

## 5. Credits

* Content
    * Google fonts - The special fonts used for the project were sourced from Google fonts.
    * Font Awesome - The icons used in the project were sourced from Font Awesome
    * W3Schools - Used the resources as a guideline for various functionality. I used parts of the code supplied in the tutorials as a guideline and adjusted it where necessary for the dropdown menu styling and functionality. The flexbox tutorial to style the summary section on the home page and the content of the Reuse, Reduce and Recycle pages. I also used the responsiveness tutorial to adjust the flexbox sections for smaller resolutions. Finally I code in thr forms tutorial to style my question form and adjusted it to fit what I required the form to show. I also used the responsive code for the form to function.
    
* Media
    * The images I used in the site were downloaded from Shutterstock using the verified licences.
    * Videos were linked directly from the respective youtube pages.