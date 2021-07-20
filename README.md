# Game Dev Portfolio

This project is a static HTML site that is used to showcase the projects I have been working on while learning C# and Unity game development.

[//]: # (Insert responsive picture here http://ami.responsivedesign.is/#)

## Table of Contents
* [Design](#design)
    * [User Stories](#user-stories)
    * [Site Mockups](#site-mockups)
* [Features](#features)
    * [All Pages](#all-pages)
    * [Home Page](#home-page)
    * [About Page](#about-page)
    * [Contact Page](#contact-page)
    * [Game Specific Pages](#game-specific-pages)
* [Testing](#testing)
    * [Functionality and Feature Testing](#functionality-and-feature-testing)
    * [Validator Testing](#validator-testing)
* [Deployment](#deployment)
* [Credits](#credits)

## Design
### User Stories
- __As an end user of the site, I want to:__
    - Be quickly presented with a clear understanding of what the website is about.
    - Be able to navigate the site with an intuitive layout, and not have to guess what to do to get where I want to go.
    - See media for the games being presented that is displayed at an easy to see size.
    - Have a clear description of what each item in the portfolio is.
    - Be able to play the games being showcased.
- __As someone using the site as a portfolio, I want to:__
    - Be able to add new items to the portfolio easily, with each one styled consistently.
    - Change the site's colour palette easily.
    - Allow site users to contact me to discuss the projects on my site.
    - Give users links to other sites etc. that can give them more information about me.

### Site Mockups
-  __Index Page__
    - ![Index Page Mockup](readme-assets/images/index-wireframe.png)
- __Portfolio Item Specific Page__
    - ![Portfolio Item Page Mockup](readme-assets/images/portfolio-item-wireframe.png)
- __About Page__
    - ![About Page Mockup](readme-assets/images/about-wireframe.png)
- __Contact Page__
    - ![Contact Page Mockup](readme-assets/images/contact-wireframe.png)

## Features

### All Pages

- __Title Bar__
    - Main title for the site, presenting a quick, single statement to the user describing what they can expect to see on the site.  
    ![Title Bar](readme-assets/images/title-bar.png)

- __Navigation Bar__
    - The responsive navigation bar is present on all pages, allowing consistent navigation between the main portfolio page, the "about me" page, and the contact form page.
    - This allows the user to access the main pages of the site without having to use browser navigation buttons.  
    ![Navigation Bar](readme-assets/images/nav-bar.png)
    - The link to the currently active page is highlighted to the user with the link underlined, and when the user moves over the non-active links, they are highlighted in the same way, giving visual feedback that the link can be clicked and will become the new active link.  
    ![Navigation Bar Link Hover](readme-assets/images/nav-bar-hover.png)
    - A high contrast colour scheme and font size is used to allow easy readability for the user.  
    ![Navigation Bar Colour and Contrast](readme-assets/images/nav-bar-contrast-check.png)

- __Always Visible Navigation__
    - Both the title bar and navigation bar stick to the top of the page, with other content hiding behind it when the page is scrolled, meaning the page navigation is always visible to the user.  
    ![Title and Navigation Always Visible](readme-assets/images/sticky-navigation.png)

### Home Page    

- __Portfolio Items__
    - This section presents the different portfolio items to the user.
    - A screenshot of the start screen is shown, followed by the title of the game, the date the game was published and a brief description of the game.  
    ![Portfolio Item Overview](readme-assets/images/portfolio-item-overview.png)
    - A "More details" button under each item's description takes the user to the dedicated page for that game.
    - This button features a high contrast underline on the text when the user hovers over it, providing visual feedback that it can be clicked on.  
    ![More Details Button Hover](readme-assets/images/more-details-button-hover.png)

### About Page
- __About Me__
    - A stylised picture of me created using https://www.bitmoji.com/ is displayed.  
    - A few short paragraphs of text describing my past career and progress into game development is placed next to the image, to give the user a quick insight into what I've done to date.  
    ![About Me Description](readme-assets/images/about-me.png)
    - Underneath the description, links to files and social media are shown, such as a link to my CV and GitHub profile.
    - These links have the same hover highlighting as the navigation bar and buttons used elsewhere in the site, providing consistent feedback on their functionality to the user.
    - The Title property on each link is set to provide a tooltip to the user, indication where the link will take them.
    - As all links are to external sites, the target for each link is set to open a new browser tab.  
    ![About Me Links](readme-assets/images/about-me-links-hover.png)

### Contact Page
- __Contact Form__
    - Presents the user with a method to contact me with a short message, supplying their name and email address to allow for a response to be sent back.  
    - Submit and form reset buttons are present to allow the user to send their message, or clear the form out if they wish to re-start or cancel sending the message.  
    ![Contact Form](readme-assets/images/contact-form.png)
    - A distinctive contrasting colour is used to highlight which section of the form is active.
    - Clicking the label next to the input element sets the cursor focus to that input.
    - All fields are required and the form will not submit if any are missed.  
    ![Contact Form Highlighting](readme-assets/images/contact-form-highlight.png)
    - The submit and form reset buttons feature the same mouse over highlighting to give the user visual feedback that the button can be clicked.  
    ![Contact Form Buttons](readme-assets/images/contact-form-button-highlight.png)

### Game Specific Pages
- __Gameplay Video__
    - A video for each game is presented to the user as the first content on the page, allowing them to preview what the game is like.  
    - The video has controls for the user to initiate and manage playback and volume. The video does not autoplay.  
    - Volume is set to default to 50%, allowing the user to set it to their own preferred levels.  
    - The same title and published date from the index page are visible below the video, maintaining consistency from the main site page.  
    ![Portfolio Item Video Preview](readme-assets/images/portfolio-specific-video.png)
    - The summary from the Index preview page, followed by some more descriptive text is shown to present the game's information to the user.
    - A "Play!" button is presented under the description, taking the user to an external page where they can play the game in a browser or install it to play on their machine.  
    - The same site wide button highlighting is used to identify to the user that the button can be clicked.  
    ![Portfolio Item Description and Play Button](readme-assets/images/portfolio-specific-description-and-button.png)
    - At the bottom of the page is a screenshot gallery, showcasing thumbnails of various images from the game.
    - The thumbnails can be clicked to open the full size image in a new browser tab / window.  
    ![Portfolio Item Screenshot Gallery](readme-assets/images/portfolio-specific-screenshots.png)



## Testing

### Functionality and Feature Testing
### User Stories
- __As an end user of the site, I want to:__
    - Be quickly presented with a clear understanding of what the website is about.  
        - The page title shows the user a quick, clear high level description of the page content.  
        ![Testing - Site Purpose](readme-assets/images/testing-site-purpose.png)
        - The About page provides the user with more information on this topic, and the link to it is one of the first things the user will see.  
        ![Testing - Site Purpose About Page](readme-assets/images/testing-site-purpose-about.png)
    - Be able to navigate the site with an intuitive layout, and not have to guess what to do to get where I want to go.
        - Links in the navigation bar are clearly defined as to their destination, and allow traversal between the key pages from each page.  
        - Links are correctly defined and take the user to the page specified.  
        ![Testing - Navbar Links - Home](readme-assets/images/testing-navbar-home.png)  
        ![Testing - Navbar Links - Home](readme-assets/images/testing-navbar-about.png)  
        ![Testing - Navbar Links - Home](readme-assets/images/testing-navbar-contact.png)  
        - Buttons on items are labelled appropriately showing where they will take the user
    - See media for the games being presented that is displayed at an easy to see size.
    - Have a clear description of what each item in the portfolio is.
    - Be able to play the games being showcased.
- __As someone using the site as a portfolio, I want to:__
    - Be able to add new items to the portfolio easily, with each one styled consistently.
    - Change the site's colour palette easily.
    - Allow site users to contact me to discuss the projects on my site.
    - Give users links to other sites etc. that can give them more information about me.
[//]: # (Insert testing screenshots once all pages in place.)

### Validator Testing
[//]: # (Insert screenshots of HTML https://validator.w3.org and CSS https://jigsaw.w3.org/css-validator/ validators when testing complete.)

## Deployment
[//]: # (Description of how to clone the GitHub repo, edit the HTML content and host the page. CSS variables for quick colour palette editing shown here.)

## Credits
Colour palette: https://coolors.co/3d5a80-98c1d9-e0fbfc-ee6c4d-293241

Fonts:
Title: https://fonts.google.com/specimen/Voltaire
Main text: https://fonts.google.com/specimen/PT+Sans

Resources:
CSS Variables: https://www.w3schools.com/css/css3_variables.asp
https://stackoverflow.com/questions/18548465/prevent-scroll-bar-from-adding-up-to-the-width-of-page-on-chrome
https://www.sitepoint.com/css-grid-web-form-layout/
https://stackoverflow.com/questions/7582385/is-there-a-way-to-set-the-default-html5-video-volume
https://fancyapps.com/docs/ui/quick-start