# Café Stop

Cafe stop is a website designed to cultivate a sense of community and connection through the joy of shared meals.  It's a morning ritual, a place where locals and visitors come together to savor the perfect start to their day.

Invites you to embark on a culinary adventure, discovering the art of breakfast and the essence of exceptional coffee.

![Cafe Stop Website showing  on all devices types](docs/mockup.png)

## Demo

Link to the live site here: <https://thiago-23.github.io/coffee-stop/>

---

# Table of contents

* [User Experience (UX)](#user-experience-ux)
  * [User Stories](#user-stories)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Icons](#icons)

* [Features](#features)
  * [Existing Features](#existing-features)
  * [Features Implementations](#features-implementations)
  * [Accessibility](#accessibility)

* [Testing](#testing)

* [Deployment and Local Development](#deployment-and-local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Solved Bugs](#solved-bugs)

* [Credits](#credits)
  * [Media](#media)
  * [Reference Material](#reference-material)

* [Acknowledgements](#acknowledgements)
  
---

## User Experience (UX)

#### The Ideal User Key information

* Where to find the locations and directions with maps for easy access.
* A structure for easy navigation, ensuring users can quickly find what they're looking for.
* A visually appealing overview of the breakfast menu and coffee selection.
* What is Cafe Stop and what does it offer?.
* A cosy ambiance, decor, and overall vibe for all audiences.

### User Stories

#### User Goals

* As a user, I want to ensure that the website loads quickly and is responsive, guaranteeing a seamless experience regardless of the device.
* As a user, I want to assure that the security of any personal information provided is protected.
* As a user, I want to know exactly where the Cafe Stop is located.
* As a user, I want to ensure that essential information such as contact details and social media links are readily accessible.
* As a user, I want to quickly access the latest breakfast offerings and any new additions to the coffee menu.

#### First-Time Visitor Goals

* As a first-time visitor, I want to View high-quality images of the Cafe Stop ambiance and signature dishes.
* As a first-time visitor, I want to Check reviews or testimonials from other first-time visitors for social proof.
* As a first-time visitor, I want to be able to find information about Cafe Stop and contact details.
* As a first-time visitor, I want to Explore the breakfast menu to get an idea of the variety available.
* As a first-time visitor, I want to understand the coffee shop's vibe, offerings, and location.

#### Returning Visitor Goals

* As a returning visitor, I want to access the latest breakfast menu to discover any new additions or seasonal specials.
* As a returning visitor, I want to Check for any events or promotions happening at Cafe Stop during my next planned visit.
* As a returning visitor, I want to Provide feedback on my previous experiences and see how it has been incorporated.

#### Frequent Visitor Goals

* As a frequent visitor, I want to Receive exclusive offers or early access to limited-time menu items as a loyal customer.
* As a frequent visitor, I want to Cafe Stop maintain transparent communication about any updates and changes

---

## Technologies Used

### Languages Used

* HTML
* CSS

---

## Design

### Colour Scheme

![Elegant Palette](docs/color-palettes.png)

### Typography

The fonts Lato and Robot used on this project were imported from [Google Fonts](https://fonts.google.com/).

### Imagery

The images used within the site were taken from [IStock](https://www.istockphoto.com/) and Google.

### Icons

The icons were taken from [Font awesome](https://fontawesome.com/icons)

---

## Features

### Existing Features

The website features a user-friendly interface with four pages(home page, menu page, gallery page and contact page).

* All pages have a logo(top left), a navigation bar, footer and a back to top button located at (button right with a yellow color).

* Navigation bar that is responsive to all screen sizes.

#### Navigation Bar

* Header Navigation Bar allows users to easily navigate from any of the pages.
* The navigation bar toggler appears with small screens such as mobile allowing users to easily navigate from all pages.
* Header Logo at the left. Clicking on the logo will return the user to the home page as expected.

![Nav Bar](docs/nav-bar.png)

#### Footer

* A footer with accessible links to social media.
* Contains social media icons, by clicking on each icon it will redirect the user to a new tab social media page.

![Footer](docs/footer.png)

#### Home Page

* The Home page consists with 3 sections:
  * Hero image:
    * Display a coffee image with a message display on the top right.
    * Having a coffee picture has the purpose to grab and give a positive impact to the user.

![Hero Image](docs/hero-image.png)

#### About Us Section

* About Us:
  * Display a message telling the users about Café Stop.
  * Containing 3 pictures about the café stop team, who we are and opening hours.
  
![About Section](docs/about-us.png)

#### Testimonials

  1. Testimonials
       * This section includes 2 customers testimonials with their experience visiting Café Stop.

![Testimonials](docs/feedback.png)

#### Menu Page

* Menu page contains a briefly message with the intention of catch the customer attention with:
  * An attractive message about the Café Stop menu.
  * A menu list with a select option of food and coffee with prices.

![Menu Page](docs/menu-list.png)

#### Gallery Page

* The gallery section has a selection of attractive images of Café Stop dishes.
* The gallery page as all pages is responsive taking one row for smaller devices, facilitating the view of each picture.

![Gallery Page](docs/gallery.png)

#### Contact

* Contact Form
  * The contact consists of four mandatory input fields where the user can enter their (first name, last name, email address and a text message). It also contains a radio button with three options (reservation, cancelation and enquiry) and a submit button where it will redirect the user to another page displaying the information entered.
  * The form contains a validation, so the users can not submit a form without filling up all the input fields.

![Contact Form](docs/contact-form.png)

* Contact Location
  * This section is to illustrate café stop locations including Google maps.

![Contact Location](docs/location-map.png)

### Features Implementations

* Create a signup page, where the users can sign in and receive information about the update menu and future events.
* Add some Animation images.
* Improve the contact page with a better form and map.
* Improve Menu page, including an animation video and an attractive menu.
* FAQ page - It gives users answers to their common questions.

### Accessibility

* The website is accessible friendly by using:
  * Semantic HTML.
  * Sufficient color contrast throughout the site.
  * Using a sans serif font, recommended for web design to be easily read.
  * Adding alt attribute to images in case the image is not loading.
  * Provide information for screen readers where the icon is used without text.

The accessibility was confirmed by running it through lighthouse in devtools.

![Café Stop accessibility](testing/accessibility.png)

---

## Testing

### W3C Validator

W3C Markup Validator were used to validate each page of the project to ensure there were no syntax errors.

[W3C Validator](https://validator.w3.org/)

* Index Page
![Index Page HTML](testing/html-validator-index.png)

* Menu Page
![Menu Page HTML](testing/html-validator-menu.png)

* Gallery Page
![Gallery Page HTML](testing/html-validator-gallery.png)

* Contact Page
![Contact Page HTML](testing/html-validator-contact.png)

### W3C CSS Validator

CSS - No syntax errors were found using Jigsaw css validator.

[Jigsaw Validator](https://jigsaw.w3.org/css-validator/)

* CSS Page
![CSS Page](testing/css-validator.png)

---

### Lighthouse

Lighthouse within the Chrome Developer Tools are used to test the performance, accessibility, best practices and SEO of the  Cafe Stop website.

* Index Page
![Index Page](testing/lighthouse-index.png)
* Menu Page
![Menu Page](testing/lighthouse-menu.png)
* Gallery Page
![Gallery Page](testing/lighthouse-galery.png)
* Contact Page
![Contact Page](testing/lighthouse-index.png)

---

## Deployment and Local Development

### Deployment

Github Pages were used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project, P01-Allotment-garden.
3. Click on the Settings link.
4. Click on the Pages link in the left-hand side navigation bar.
5. In the Source section, choose main from the drop-down select branch menu. Select Root from the drop-down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

To fork the P01-Allotment-gardens repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, Zest-studi-o/P01-Allotment-gardens.
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the P01-Allotment-gardens repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, Zest-studi-o/P01-Allotment-gardens.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

---

## Solved Bugs

After asking friends and family to test the deploy Cafe Stop Project, it was identified the following bugs and fixed action were taken.

1. The gallery page:
   * It was not responsive with small devices.
   * Fixed by changing the width to 80% and was able to make it responsive.
2. Contact-row information:
   * It was not centred on laptop devices with 1440p.
   * Fixed by creating a media query and adding .contact-col div into it.
3. Contact form:
   * It was working with some empty fields.
   * Fixed by add required to input field and it is now mandatory.
4. Submit button background color:
   * It brought the performance to a low score.
   * Fixed by changing the text to a dark color and it improved the score.
5. Location details:
   * Was not displayed as a list on small devices.
   * Fixed by changed to display: inline on media query max-width:700px.
6. Textarea:
   * Placeholder text on contact form was close to the text box edge.
   * Fixed by adding some padding and it gave more space around the textarea form.
7. Menu section:
   * The menu page was close to the footer without space.
   * Fixed by adding a padding-button.

---

## Credits

## Media

* [IStock](https://www.istockphoto.com/)
* [Font awesome](https://fontawesome.com/icons)
* [Iconmonstr](https://iconmonstr.com/?s=coffee)
* [Coolors](https://coolors.co/)
* [You Tube Flexbox Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9i3FXJSUfmsNOx8E7u6UuhG)
* [Google Fonts](https://fonts.google.com/)
* [Mockup Screenshot Generator](https://ui.dev/amiresponsive)

## Reference Material

* [Love Running Walkthrough project](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/8.1-testing-and-validation)
* [Love Running Walkthrough project readme template](https://github.com/Code-Institute-Solutions/readme-template)
* [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [W3 School](https://www.w3schools.com/)
* [Stackoverflow - Back to top button](https://stackoverflow.com/search?q=back+to+top+button)

---

## Acknowledgements

* [Derek McAuley](https://github.com/derekmcauley7), My code institute Mentor who supports and clarifies all my queries.
* Tutor Assistance at Code institute when I had an issue with codeanywhere.
