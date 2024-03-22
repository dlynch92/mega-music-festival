# Mega Music Festival

Mega Music Festival is a music festival in the UK - the website is designed both to advertise the festival and provide useful information for people who are already interested.

The index page shows the announced bands via a poster as well as some information on the festival and a google maps iframe to assist in locating the festival premises.Tickets are distributed via a waitlist on the ticket page that users can enter their details on and specify how many tickets they want, with information regarding the outcome provided to them at a later date. There is also a gallery page featuring images from past editions of the festival.

Links to social media are on the footer of each page where users can contact the festival organisers with any queries they may have.

![Am I Responsive](/assets/images/am-i-responsive.webp)

[Mega Music Festival live project](https://dlynch92.github.io/mega-music-festival/)
- - -
## Table of Contents

### [User Experience (UX)](#user-experience-ux-1)
### [Design](#design-1)
### [Features](#features-1)
### [Technologies Used](#technologies-used-1)
### [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used-1)
### [Testing](#testing-1)
* [Validation Results](#validation)
* [Lighthouse Report](#lighthouse)
* [Manual Testing](#manual-testing)
* [Bugs Fixed](#bugs-fixed)
### [Deployment and local development](#deployment-and-local-development-1)
* [GitHub Pages](#github-pages)
* [Forking the GitHub Repository](#forking-the-github-repository)
* [Local Clone](#local-clone)
### [Credits](#credits-1)
### [Acknowledgements](#acknowledgements-1)
---

## User Experience (UX)

This website is designed to be attractive to people who are into metal and industrial music and who would be likely to attend a festival hosting music of that type.

At the top of each page is a navigation bar that is consistent throughout the pages that allows users to navigate to the various pages of the website.

Users purpose on the site may be different if they are a first time user or a returning user, the purpose of these different user groups are identified as follows: 

* First-time visitors
    * Quickly establish the purpose of the website.
    * Learn of the bands that will be playing.
    * Navigate using the navigation bar to the various pages and learn about the festival.
    * Apply for tickets if they are sufficiently interested.

* Returning visitors
    * Check the bands that are playing and see if there are new ones since their last visit.
    * Use the google maps iframe to plan how to get to the festival if they are planning on going.
    * See if any further information has been posted regarding the festival and ticket aquisition.
    * If they hadn't previously they will also be able to apply for tickets if they are sufficiently interested.
---

## Design

I designed the website mobile first as I felt it would be easier to expand to larger screens than to shrink content to smaller ones.  

When submitting the ticket form users are taken to the thank-you page that is identical to the ticket page except for the form, which disappears and is replaced by a thank you message. I thought this would be good and intuitive as it would give the impression users have not left the ticket page as only the form had been submitted.

As the website is simple and static I did not create any proper wireframes, however I did draw very basic concepts for a mobile layout showing the header / content / footer on pen and paper.

 * Colour Scheme
    * The colours used on the website are as follows:
    ![Colour Palette](/assets/images/palette.png)
    * Colour palette was generated with the help of [Colormind.io](http://colormind.io/)

 * Typography
    * Headers used the Metal Mania font with a fallback of system-ui if it failed to import.
    * Paragraphs and other content used the Roboto font with a fallback of sans-serif if it failed to import.
 
---

## Features

 * A simply to navigate website aimed at people who enjoy metal and industrial music and who may want to attend a festival of that music.
 * The user can fill out a form to show their interest in obtaining tickets.
 * Interactable Google Maps iframe showing where the festival will be held.
 * The background on each page is a subtle gradient starting below the hero image at black and slowly changing to a dark purple. Originally the background was to be all black but this looked boring and so I thought to include a gradient that would subtly change the visual style of the page the further the user went down.
 * Responsive on all device sizes.

### Navigation Bar
![Navigation Bar](/assets/images/nav-bar.png)
* The navigation bar is present on every page and shows in a different colour which page the user is currently on.
* Links to the home page, ticket page and gallery.
* Does not link to the thank you page that is accessed after submitting the form, and this page is designed to look identical to the ticket page. From a users' perspective it is like that haven't left the ticket page and so including the thank you page on the nav bar would detract from this idea and not serve a purpose.

### Hero Image
![Hero Image](/assets/images/readme-hero.png)
* A different hero image is present on each page to add variety and keep the user visually engaged.
* The image is the same size on each page for consistency.
* Over the image is some text - on the homepage (shown above) it shows a general message of ticket waitlist now available, which sums up the current purpose of the website in that we want users to sign up to the ticket waitlist. The other pages show a more specialised message that sums up the purpose of that particular page. 

### Google Maps iframe
![Google Maps](/assets/images/google-map.png)
* At the bottom of the index page is an interactable Google Maps iframe that spans the width of the page in order to assist the user in planning how they would get to the festival.
* Clicking the View Larger Map button opens the map on a seperate tab.

### Footer
![Footer](/assets/images/footer.png)
* The footer is identical on each page for consistency.
* The icons of the various social media buttons and clickable and will link the user to the relevant social media webpage.
* Clicking on a button opens the page in a new window.
* Displays copyright information below social media links

### Ticket Form
![Footer](/assets/images/ticket-form.png)
* Displays on the ticket page and is for the user to enter their details to apply for tickets.
* All fields are required.
* Email address field includes validation to ensure an email address has been entered in the correct formatting.
* A user is able to apply maximum of 4 tickets as is referenced throughout the website - when picking how many tickets the user will want only the options 1-4 are displayed.
* Clicking Apply submits the data if all fields are entered correctly and transports the user to the thank-you page, which functionally looks the same as the ticket page except for the form itself which now displays a message saying they will recieve an email shortly.
* Clear form resets all data to their defaults.

## Gallery
![Gallery](/assets/images/gallery.png)
* A responsive page using flexbox that shows images from past editions of the festival designed to entice users into signing up for tickets.
* On viewports below 400px only 1 image will display per row.
---

## Technologies Used

 * [HTML5](https://en.wikipedia.org/wiki/HTML5)
 * [CSS3](https://en.wikipedia.org/wiki/CSS)

---

## Frameworks, Libraries & Programs Used

 * [Visual Studio Code](https://code.visualstudio.com/)
    * To write the code.
 * [Git](https://git-scm.com/)
    * for version control.
 * [Github](https://github.com/)
    * Deployment of the website and storing the files online.
 * [Google Fonts](https://fonts.google.com/)
    * Import fonts for the website.
* [Am I Responsive](https://ui.dev/amiresponsive)
    * Mockup picture for the README file.
* [Font Awesome](https://fontawesome.com/kits)
    * Icons used throughout the website.
---

## Testing

I tested the website with three seperate methods. Firstly, each page was ran through the W3C validator. Secondly I ran a Lighthouse Report in order to see an analysis of how each page performed.

Lastly was manual testing - this was a case of me running the website and resizing it on different browsers and OS to ensure everything on the page worked as in different environments. I will go more in depth with each of these below.

### Validation

 * HTML pages were validated using the [W3C Markup Validtor](https://validator.w3.org/)
 * The style.css sheet was validated using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

 All four html pages and the stylesheet display no errors.

 ![HTML Validator showing no errors](/assets/images/validator-no-errors.png)

 ![CSS Validator showing no errors](/assets/images/validator-css-no-errors.png)

### Lighthouse

During testing with lighthouse I found several accessibility issues that I fixed.
  * Added a title to the Google Maps iframe
  * Added aria-title to the social media links

Several performance issues mostly stemming from filesizes being too big were also pointed out to me - I reduced the dimensions of the poster and the index circular images in order to help with this.

#### Mobile Analysis

<details>
<summary>Home Page</summary>

![Home Page lighthouse report](/assets/images/lighthouse-main-mobile.png)
</details>

<details>
<summary>Tickets</summary>

![Home Page lighthouse report](/assets/images/lighthouse-tickets-mobile.png)
</details>

<details>
<summary>Thank You</summary>

![Home Page lighthouse report](/assets/images/lighthouse-thankyou-mobile.png)
</details>

<details>
<summary>Gallery</summary>

![Home Page lighthouse report](/assets/images/lighthouse-gallery-mobile.png)
</details>


#### Desktop Analysis

<details>
<summary>Home Page</summary>

![Home Page lighthouse report](/assets/images/lighthouse-main-desktop.png)
</details>

<details>
<summary>Tickets</summary>

![Home Page lighthouse report](/assets/images/lighthouse-tickets-desktop.png)
</details>

<details>
<summary>Thank You</summary>

![Home Page lighthouse report](/assets/images/lighthouse-thankyou-desktop.png)
</details>

<details>
<summary>Gallery</summary>

![Home Page lighthouse report](/assets/images/lighthouse-gallery-desktop.png)
</details>

### Manual Testing
* Tests were carried out on Windows 11 using the Google Chrome and Microsoft Edge browsers.
* Tests were carries out on MacOS 11 using the Google Chrome and Safari Browser
* The website was viewed using Chrome dev tools in various different screen sizes to ensure everything looked as it should on mobile and tablet devices.
* All internal and external links were tested to ensure they open correctly - internal links on the same tab and external in a new tab.

### Bugs Fixed
* Links to social media pages in footer of each page weren't working. I was using for example www.facebook.com which is still a relative filepath - changing these links on each page to include https:// made it absolute and fixed the issue, they now work as intended.
* The aspect ratio of the Circle images on the home page were slightly incorrect - I fixed this by setting height, width and aspect ratio to auto.
* Lighthouse reports were not showing on the deployed README.md despite showing in preview. I had typed the files with a .PNG extension when they were .png - I changed this and now they work.
---

## Deployment and local development

### GitHub Pages

GitHub Pages used to deploy live version of the website.
1. Log in to GitHub and locate [GitHub Repository Mega Music Festival](https://github.com/dlynch92/mega-music-festival)
2. At the top of the Repository(not the main navigation) locate "Settings" button on the menu.
3. Scroll down the Settings page until you locate "GitHub Pages".
4. Under "Source", click the dropdown menu "None" and select "Main" and click "Save".
5. The page will automatically refresh.
6. Scroll back to locate the now-published site [link](https://dlynch92.github.io/mega-music-festival/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the repository, we make a copy of the original repository on our GitHub account to view and change without affecting the original repository by using these steps:

1. Log in to GitHub and locate [GitHub Repository Mega Music Festival](https://github.com/dlynch92/mega-music-festival)
2. At the top of the Repository(under the main navigation) locate "Fork" button.
3. Now you should have a copy of the original repository in your GitHub account.

### Local Clone

1. Log in to GitHub and locate [GitHub Repository Mega Music Festival](https://github.com/dlynch92/mega-music-festival)
2. Under the repository name click "Clone or download"
3. Click on the code button, select clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone` and then paste The URL copied in the step 3.
7. Press Enter and your local clone will be created.
---

## Credits

* All code written by myself
* Stock images royalty free from [Pexels](https://www.pexels.com/)
* Lineup poster created with [Festival Poster Generator](https://festivalpostergenerator.com/)
* README template provided by [Thomas-Tomo - Lunar-Escape](https://github.com/Thomas-Tomo/Lunar-Escape/blob/main/README.md)
* Favicon generated with  [Favicon.io](https://favicon.io/)
---

## Acknowledgements

* My mentor Mitko Bachvarov for tips and encouragement.
* [Flexbox Zombies](https://mastery.games/flexboxzombies/) by Mastery Games for a very helpful game that helped me learn Flexbox.
* [css-tricks.com](https://css-tricks.com/adaptive-photo-layout-with-flexbox/) for the idea of putting gallery images as an unordered list.