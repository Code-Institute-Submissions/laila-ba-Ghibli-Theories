# Ghibli Theories


## Overview

Ghibli Theories is a webiste that focuses on bringing Studio Ghibli fans a simple and easy platform to share and learn about new Ghibli based theories. Its main purpose is to keep fans up to date with the latest news and stories while allowing users to post, edit and delete their posts. 

## User Stories
- User Goals

  a. As a user, i want to be able to access the site from any device.
  
  b. As a user, i want to find using the website's functionality simple with clear instructions.
  
  c. As a user, i want to have full control over my account following computer programming CRUD (create, read, update & delete) operations.
  
  d. As a user, i want to have full control of my created posts following computer programming CRUD (create, read, update & delete) operations.

- First time visitor Goals


  a. As a first time user, i want to be able to immediately and clearly understand the purpose of the website.
  
  b. As a first time user, i want to be able to create an account quickly and securely.
  
  c. As a first time user, i want to find the UI eye-catching, clear and aesthetically pleasing.
  
  - Returning visitor Goals

  a. As a returning visitor, i want to be able to serach the site for theory that i want.
  
  b. As a returning visitor, i want to be able to manage my own posts either by editing or deleting them.
  
  ## Strategy
  
  As the creator of this site, the main goal is to convert the visitors into registered, active users with the website. In order to do this, there will need to be actions that only registered users are able to carry out. For an example, post and edit their own theories to be a part of the community. The landing page must also play a huge part as it is the first thing the users will come across and ultimately, draws them in to engage with the wesbite. This will be done using a fun and continuous color scheme with eye-catching images that the first time users will recognise. There will also be a simple yet engaging summary on the landing page that catches the users attention into clicking the browse button and taking a look at the theories. 
 
There will also be a 'sneak peek' section where unregistered users will be able to see some theories that are deafault with the webiste, however no users posts will appear. This will gain their attention to register so that they can have access to all posts.

  ## Scope
  
  Features within the initial design:
  
  - A fully responsive website, can be viewed on any device.
  
  - buttons on landing page peruading user to browse theories and register
  
  - allowing users to create and manage their own accounts
    - This includes editing and deleting their posts.
  
  - registered users can search the browse page for theories.

  - My site will include sub pages such as: Home, browse, Add, Pofile, login, logout, register
    - sub pages such as browse, add, profile and login will only be available to registered users that are signed into their account.
  
  - Once a user adds a theory and posts it, it is visible to the community on the browse page.

  - The browse page will include a section for theories posted by the websites creator and another section posted by the community.

  ## Structure
  
  The structure of the site will be:
  
  #### Navigation Bar 
  
   - The navigation bar will be simple and easy to use that turns into a hamburger menu when viewed on small screen.
   - When the hamburger menu is clicked, i dropdown menu appears with the subpages.
 
 #### Landing Page 
 
   - A vibrant hero image with the webiste name will appear in big bold writing with a short and simple summary bellow. A button will be placed bellow for 'Browse Theories' to      allow easy naviagtion. For unregistered users, this takes them to the register page and for registered users, this takes them to the browse page.
    
   - Below the hero image, a small section will appear with the title 'join the community' and a register button, again, for easy navigation while making the signing up process       easy and simple for the user.
    
   - There will be a 'sneak peak' section with a small amount of theories that draws new users to the site and allows them to see what the wesbite is all about. The theories         that appear in this section are posted by the webistes creator.
     - When these are clicked on, a larger page appears with an enlarged image and text for the user to easily read. There is a close icon at the top of the page and a close          button at the button.
      
   - Underneath this area, there is a small section with the title of 'want to see more?' that redirects users to the register page. The redirects to the register page persuade      the user to signup to have full access of the webiste without any hassle.
    
  #### Browse Page 
  
  - At the top of the browse page, there will be a search bar which will enable the user to search through the communities posts, the results will be filtered through the theory     names and descriptions. 
  - section bellow will be the theories that are posted by the webistes creator which have a clear difference in styling.

#### Login, register, add post, edit post 

  - These pages that are using forms will have only the forms as content in order for that to be the main focus point.

#### Profile 

  - The profile page will show the users username along side their posts while also giving them an option to add a post. Each of their posts will have an option to edit and         delete. If the user chooses to delete the post, a modal pop appears asking the user again if they want to delete. This is added for precaution just in case the user has clicked delete by accident .

## Mockups

- [Desktop webiste view](https://github.com/laila-ba/Ghibli-Theories/blob/main/mockups/desktop%20view.pdf)
- [Mobile webiste view](https://github.com/laila-ba/Ghibli-Theories/blob/main/mockups/mobile%20view.pdf)

## Design

#### Colour Scheme
- The colour scheme for this webiste evolves around the hero image on the landing page. It contains tones of royal blue and orange. Throughout the whole site, i have chosen to use dark blue, orange, and green. These fun colours stand out nicely against white backgrounds without appearing too much on the eye. They also portray the fun and magical feel that the ghibli films offer to their fans.

- Dark navy blue (#1d438a) - This is one of the main primary colours of the site used alongside orange. It goes well with the website as it carries on the deep sea theme that the hero image on the landing page conveys. It used for: banners of information and image titles for ghibli posts.

- Coral Orange (#f4623a)- Taken from the hero image, this coral colour is adapted alot more throughout the site, being the primary colour across the project. The contrast between the blue and orange works niceley and go both hand in hand. Its used for: the logo, dividers underneath titles, url buttons, hovering over nav sub-pages and community post titles

- Green (#008000) and Red(#ff0000)- A hint of green and red are used on the profile page for the edit and delete buttons in order to stand out to the user as both buttons allow the user to manage their data.

#### Typography
 There are two fonts used througout the site : "Merriweather" and "Merriweather-Sans"
 
 - I wanted to use a combination of two fonts in order to not make the site boring and plain. "Merriweather-Sans" i used for big title texts and buttons as its slightly more thicker and bolder, whereas "Merriweather" is used for the text on posts and larger quantities of information.

#### Logo

The logo for this project was designed and created by myself while using Adobe Illustrator. I wanted to implement the Striking orange colour from the hero image as it would contrast well against the white navigation bar. I wanted to keep the logo simple, with no text in order to keep a clean and sleak aesthetic.

#### Imagery

- Images appear the most on the landing page to attract and show the sites visitors what the websites focus is. Using high quality images from ghibli films keeps the ghibli aesthetic strong and attracts more users to the site, ultimately converting them into registered, active users. Images such as the hero image is used on the landing page, login,logout,add and edit pages in order to keep the pages exciting and not bland.

## Database Model
For this project i chose to use MongoDB for all database aspects in order to become more familar with it through practise and development.MongoDB stores data in flexible, JSON-like documents, meaning fields can vary from document to document and data structure can be changed over time.

- Using 12-bit-MongoDB-specific unique values such as ObjectId's can be used to identify objects within the Database as it is used by MongoDB to search for a specific ObjectID.This is used within my project in order for my site to run smoothly, allowing users to manage their data.
  

  
