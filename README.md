# Game Dev Portfolio

This project is a static HTML site that is used to showcase the projects I have been working on while learning C# and Unity game development.

![Game Dev Portfolio Responsive Preview](readme-assets/images/gamedev-portfolio-responsive-preview.png)

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
        * [User Stories](#user-story-testing)
        * [Browser Testing](#browser-testing)
            * [Firefox on Windows](#firefox-on-windows-desktop)
            * [Chrome on Windows](#chrome-on-windows-desktop)
            * [Firefox on Android](#firefox-on-android)
            * [Chrome on Android](#chrome-on-android)
    * [Validator Testing](#validator-testing)
* [Deployment](#deployment)
* [Credits](#credits)

# Design
## User Stories
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

## Site Mockups
### Index Page
    ![Index Page Mockup](readme-assets/images/index-wireframe.png)
### Portfolio Item Specific Page
    ![Portfolio Item Page Mockup](readme-assets/images/portfolio-item-wireframe.png)
### About Page
    ![About Page Mockup](readme-assets/images/about-wireframe.png)
### Contact Page
    ![Contact Page Mockup](readme-assets/images/contact-wireframe.png)

# Features
## All Pages
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

## Home Page    
- __Portfolio Items__
    - This section presents the different portfolio items to the user.
    - A screenshot of the start screen is shown, followed by the title of the game, the date the game was published and a brief description of the game.  
    ![Portfolio Item Overview](readme-assets/images/portfolio-item-overview.png)
    - A "More details" button under each item's description takes the user to the dedicated page for that game.
    - This button features a high contrast underline on the text when the user hovers over it, providing visual feedback that it can be clicked on.  
    ![More Details Button Hover](readme-assets/images/more-details-button-hover.png)

## About Page
- __About Me__
    - A stylised picture of me created using https://www.bitmoji.com/ is displayed.  
    - A few short paragraphs of text describing my past career and progress into game development is placed next to the image, to give the user a quick insight into what I've done to date.  
    ![About Me Description](readme-assets/images/about-me.png)
    - Underneath the description, links to files and social media are shown, such as a link to my CV and GitHub profile.
    - These links have the same hover highlighting as the navigation bar and buttons used elsewhere in the site, providing consistent feedback on their functionality to the user.
    - The Title property on each link is set to provide a tooltip to the user, indication where the link will take them.
    - As all links are to external sites, the target for each link is set to open a new browser tab.  
    ![About Me Links](readme-assets/images/about-me-links-hover.png)

## Contact Page
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

## Game Specific Pages
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

# Testing
## Functionality and Feature Testing
## User Story Testing
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
        ![Testing - Navbar Links - About](readme-assets/images/testing-navbar-about.png)  
        ![Testing - Navbar Links - Contact](readme-assets/images/testing-navbar-contact.png)  
        - Buttons on items are labelled appropriately showing where they will take the user  
        ![Testing - Buttons - More Details](readme-assets/images/testing-button-moredetails.png)  
    - See media for the games being presented that is displayed at an easy to see size.  
        - Each project has a video as the first element that is set to display at an easily viewable size.  
        - Media controls exist for the videos allowing the user to control its playback.  
        ![Testing - Media - Video](readme-assets/images/testing-media-video.png)  
        - A screenshot gallery is present at the bottom of each portfolio page.  
        ![Testing - Media - Screenshots](readme-assets/images/testing-media-screenshots.png)  
        - Clicking the gallery thumbnail enlarges the image to make it more easily viewable.  
        ![Testing - Media - Large Screenshot](readme-assets/images/testing-media-large-screenshot.png)  
    - Have a clear description of what each item in the portfolio is.  
        - Each portfolio item has a quick summary on the main index page, and a detailed description on its dedicated page.  
        ![Testing - Project Description](readme-assets/images/testing-project-description.png)  
    - Be able to play the games being showcased.  
        - Each game has a clear "Play" button on its dedicated page, taking the user to an external page where the game can be played.  
        ![Testing - Play Game Button](readme-assets/images/testing-play-button.png)
- __As someone using the site as a portfolio, I want to:__
    - Be able to add new items to the portfolio easily, with each one styled consistently.
        - A "game-page-template.html" page has been created with the basic structure of a project page included, allowing it to be quickly duplicated and content added.
    - Change the site's colour palette easily.
        - The stylesheet for the site uses root variables to define the colours for items, with clearly named variables. Changing the root variable definition will change all elements using that colour.  
        ![Testing - Variables](readme-assets/images/testing-variables.png)  
        - Changing the header background colour variable, and the effect it has:
        ![Testing - Variable Changed](readme-assets/images/testing-colour-variable-changed.png)  
        ![Testing - Variable Changed Effect](readme-assets/images/testing-colour-variable-changed-effect.png)  
    - Allow site users to contact me to discuss the projects on my site.
        - The contact page allows users to send me a plain text message.
        - Note that this is currently inoperational during development, however the submit button has the correct definition and is just missing a target to send the data to.
    - Give users links to other sites etc. that can give them more information about me.
        - The About page has a series of links to other sites that provide more information about me.
        ![Testing - Additional Links](readme-assets/images/testing-additional-links.png) 
## Browser Testing
The site and all functionality has been tested in the following browsers:
### Firefox on Windows Desktop:  
![Firefox - Home](readme-assets/images/browser-test-firefox-home.png)  
![Firefox - About](readme-assets/images/browser-test-firefox-about.png)   
![Firefox - Contact](readme-assets/images/browser-test-firefox-contact.png)  
![Firefox - Portfolio](readme-assets/images/browser-test-firefox-portfolio.png)  
### Chrome on Windows Desktop:  
![Chrome - Home](readme-assets/images/browser-test-chrome-home.png)  
![Chrome - About](readme-assets/images/browser-test-chrome-about.png)   
![Chrome - Contact](readme-assets/images/browser-test-chrome-contact.png)  
![Chrome - Portfolio](readme-assets/images/browser-test-chrome-portfolio.png)  
### Firefox on Android:  
![Firefox - Android - Home](readme-assets/images/browser-test-firefox-android-home.jpg)  
![Firefox - Android - About](readme-assets/images/browser-test-firefox-android-about.jpg)  
![Firefox - Android - Contact](readme-assets/images/browser-test-firefox-android-contact.jpg)  
![Firefox - Android - Portfolio](readme-assets/images/browser-test-firefox-android-portfolio.jpg)  
### Chrome on Android:  
![Chrome - Android - Home](readme-assets/images/browser-test-chrome-android-home.jpg)  
![Chrome - Android - About](readme-assets/images/browser-test-chrome-android-about.jpg)  
![Chrome - Android - Contact](readme-assets/images/browser-test-chrome-android-contact.jpg)  
![Chrome - Android - Portfolio](readme-assets/images/browser-test-chrome-android-portfolio.jpg)  
## Validator Testing
- __The site has been tested with the following validators:__
    - ### HTML:
    - [W3C HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fsijil82.github.io%2Fgame-dev-portfolio%2F)  
    - No issues found:  
    ![HTML Validator](readme-assets/images/testing-html-validation.png)  
    - ### CSS
    - [W3C CSS Validation](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fsijil82.github.io%2Fgame-dev-portfolio%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)  
    - A number of warnings and errors are returned, however these are all because the validator tool is not up to date with the current CSS specifications.
    ![CSS Validator Errors](readme-assets/images/css-validation-errors.png)  
    ![CSS Validator Warnings](readme-assets/images/css-validation-warnings.png)  
    - The "Value Error : border-bottom Invalid RGB function ) ", "Invalid RGB function )" errors and "is an unknown vendor extension" warnings are due to the validator not supporting custom CSS properties, which have been a valid part of the CSS specification for a number of years, as per https://github.com/w3c/css-validator/pull/173  
    - The "Property text-underline-offset doesn't exist" error is also because the validator has not been updated with the addition of this valid CSS property, as per https://developer.mozilla.org/en-US/docs/Web/CSS/text-underline-offset  

# Deployment
- __To view the deployed project:__
    - The project is currently deployed to GitHub pages and can be viewed at https://sijil82.github.io/game-dev-portfolio/
- __To deploy a copy of the project:__
    - Open the GitHub repository at https://github.com/SiJiL82/game-dev-portfolio
    - Click the "Code" button and clone the repository locally.
    - Set the remote repository in your local clone with the command: `git remote set-url origin http://github.com/YOU/YOUR_REPO`
    - Adjust the page content to display your portfolio items as appropriate, and push the changes to your repository.
    - In the GitHub repository, click on the Settings button.
    - Click the Pages tab on the left-hand menu.
    - Select "Master" or "Main" from the Source drop down list.
    - Click Save.
    - GitHub will build and publish the site and provide a link to the public facing address.
        - Note that this can take up to 5 minutes to fully deploy.

# Credits
- __The following resources were used while developing this project:__
    - Colour palette: [coolors.co](https://coolors.co/3d5a80-98c1d9-e0fbfc-ee6c4d-293241)  
    - Fonts:
        - Title: [Google Fonts - Voltaire](https://fonts.google.com/specimen/Voltaire)
        - Main text: [Google Fonts - PT Sans](https://fonts.google.com/specimen/PT+Sans)  
    - Image thumbnail to full size functionality: [Fancy Apps](https://fancyapps.com/docs/ui/quick-start)
    - CSS Variables documentation: [W3 Schools - CSS Variables](https://www.w3schools.com/css/css3_variables.asp)
    - Set page to not count scrollbar as content width: [Stack overflow](https://stackoverflow.com/questions/18548465/prevent-scroll-bar-from-adding-up-to-the-width-of-page-on-chrome)
    - Contact form grid layout: [Sitepoint](https://www.sitepoint.com/css-grid-web-form-layout/)
    - Inline script to default video player volume to 50%: [Stack overflow](https://stackoverflow.com/questions/7582385/is-there-a-way-to-set-the-default-html5-video-volume)
- __Additional mentions:__
    - I would like to thank my Code Institute mentor Tim Nelson for his encouragement, support and insight while developing the project.
