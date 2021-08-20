# Ghibli Theories

![Untitled](https://user-images.githubusercontent.com/75024926/130273638-6c406986-ad01-4d31-a128-f7939f44728c.png)


## Overview

Ghibli Theories is a webiste that focuses on bringing Studio Ghibli fans a simple and easy platform to share and learn about new Ghibli based theories. Its main purpose is to keep fans up to date with the latest news and stories while allowing users to post, edit and delete their posts. 

## User Stories
- User Goals
  
  a. As a user, i want to find using the website's functionality simple with clear instructions.
  
  b. As a user, i want to have full control of my created posts following computer programming CRUD (create, read, update & delete) operations.

- First time visitor Goals
  
  a. As a first time user, i want to be able to create an account quickly and securely.
  
  - Returning visitor Goals

  a. As a returning visitor, i want to be able to serach the site for theory that i want.
 
  
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
  
  #### Navigation Bar 
  
   - The navigation bar will be simple and easy to use that turns into a hamburger menu when viewed on small screen.
   - When the hamburger menu is clicked, a dropdown menu appears with the subpages. When the dropdown menu appears, the content bellow moves down allowing no content to be            hidden underneath the navigation bar.
 
 #### Landing Page 
 
   - A vibrant hero image with the webiste name will appear in big bold writing with a short and simple summary bellow. A button will be placed bellow for 'Browse Theories' to      allow easy naviagtion. For unregistered users, this takes them to the register page and for registered users, this takes them to the browse page.
    
   - Below the hero image, a small section will appear with the title 'join the community' and a register button, again, for easy navigation while making the signing up process       easy and simple for the user.
    
   - There will be a 'sneak peak' section with a small amount of theories that draws new users to the site and allows them to see what the wesbite is all about. The theories         that appear in this section are posted by the webistes creator.
     - When these are clicked on, a larger page appears with an enlarged image and text for the user to easily read. There is a close icon at the top of the page and a close          button at the button.
      
   - Underneath this area, there is a small section with the title of 'want to see more?' that redirects users to the register page. The redirects to the register page persuade      the user to signup to have full access of the webiste without any hassle.
    
  #### Browse Page 
  
  - At the top of the browse page, there will be a search bar which will enable the user to search through the communities posts, the results will be filtered through the theory     names and descriptions. Besides this is a 'clear' button allowing the search bar and results to be reset. 
  - section bellow will be the theories that are posted by the webiste's creator which have a clear difference in styling.
  - When viewed on mobile, The posts appear on top of eachother rather than besides eachother, making it easier and more efficient to view on smaller devices.
  - The browse page is only visible to registered users so that posts are only seen within the community.

#### Login, register, add post, edit post 

  - The forms used on these pages are all the same, keeping the same aesthetic throughout the webiste.
  - The add and edit forms can be only be accessed by registered users.

#### 404

- A custom 404 error page for when a user tries to access a page that doesnt fit their current state. e.g: the user attempts to register while being logged in. The 404 page has a link that takes them back to the home page and an image that fits well with the aesthetic of the webisite.

#### Profile 

  - The profile page will show the users username along side their posts while also giving them an option to add a post. Each of their posts will have an option to edit and         delete. If the user chooses to delete the post, a modal pop appears asking the user again if they want to delete. This is added for precaution just in case the user has clicked delete by accident . The profile page follows CRUD operations as it allows users to add, edit and delete their posts easily. Once posts are deleted, they are also removed from the browse section and will no longer be visible to the community
  - When posts are added, edited or deleted, flash messages will appear letting the user know that it has been successful

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

![database model](https://user-images.githubusercontent.com/75024926/130251989-16ea9f50-c077-48b8-b79a-80f0abd5940f.png)

Above, we have the posts collection that contains a users post when added and the users collection, containing login info. Within both collections, the ObjectID is present so that the data can be manipulated and the DB can be searched.

## Future Features

- Add like and dislike buttons to users posts, allowing the community to engage with one another
- Added a newletter signup that would send registered users the latest theories by emailJS

## Technologies Used 

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
  * This is used a the base of the code. It structures the code and acts as the main building block

* [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
  * This allows styling to be added to the project.

* [Hover.css](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/hover)
  * Hover effect used for the social icons, navbar, and portfolio.

* [Bootstrap](https://getbootstrap.com/L)
  * A framework to make the project responsive

* [jQuery](https://jquery.com/)
  * A framework used with Javascript

* [Font Awesome](https://fontawesome.com/)
  * Used to obtain icons used for the footer and contact page.

* [Google Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
  * Used to help debug the code and help find syntax errors.

* [Github](https://github.com/)
  * Used to push and store the code.

* [Atom](https://atom.io/)
  * Used as the IDE and the development environment for writing the code.

* [JS validator](https://jshint.com/)
  * Used as a JS validator

* [HTML validator](https://validator.w3.org/)
  * Used as a HTML validator
  
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
  * Used as a CSS validator

* [Grammarly](https://www.grammarly.com/)
  * Used to check and correct grammatical errors across the project.

* [Python Validator](https://extendsclass.com/python-tester.html)
  * Used as a python validator
  
* [Canva](https://www.canva.com/)
  * Used to create mockups 

* [am i responsive](http://ami.responsivedesign.is/#)
  * A site used to see if my project is responsive

* [jinja](https://jinja.palletsprojects.com/en/3.0.x/)
  * A web template engine for python.

* [PyMongo](https://pymongo.readthedocs.io/en/stable/)
  * A python distribution containing tools for working with MongoDb

* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
  * A micro web framework written in python

* [heroku](https://en.wikipedia.org/wiki/Heroku)
  * A cloud platform service supporting numerous languages

* [MongoDB](https://www.mongodb.com/)
  * The database platform used for this project.

## Testing

  #### HTML Validation 
  
  Once i had finished the code for the project and put the URL into the validators, these were the main errors that appeared and how i resolved them:
  
   - "A slash was not immediately followed by >"
       " alt="close"//></div>↩"    
       - This was shown on multiple lines that had the img src for the close icon. I resolved this by removing the extra '/' on every line.
        - There were no other errors present

 #### CSS Validation 
 
  - Value Error : color Lexical error at line 3880, column 11. Encountered: "#" (35), after : "#" #00709c;
     
     - These errors were shown on multiple lines for extra hashtags for colour codes. I resolved this by removing the extra tags.
      - There were no other errors present

#### JS Validation 

  - The main errors i recieved were missing or unessesary semi colons which were resolved by adding and removing them.
    - There were no other errors present

#### Python Validation

  - There were no other errors present

## User Story Testing 

"As a user, i want to find using the website's functionality simple and easy to use."

  - Users a greeted with a short and simple summary on the landing page with a link to the browse page. Through the summary, they are able to understand immediately what the         site's focus is.
  
   ![objectID2](https://user-images.githubusercontent.com/75024926/130268776-5a903380-b7c3-4101-a4b3-966c608b3180.png)
   
   - Form input fields are clear and simple to proceed to fill it in. Users can post theories easily without hassle.
   
  ![objectID2](https://user-images.githubusercontent.com/75024926/130270215-aab87839-9656-47df-bb28-46d721948d6f.png)
  
   "As a user, i want to have full control of my created posts following computer programming CRUD (create, read, update & delete) operations."
    
   - Users have full control of their posts as they can create, read, update and delete. My project has implemented CRUD functionality in order for the user to manage their posts.
   ![Untitled](https://user-images.githubusercontent.com/75024926/130270915-20d24c32-9b00-485b-b205-bdc5628be3bf.png)
   ![Untitled](https://user-images.githubusercontent.com/75024926/130271151-388f0bb2-ea3b-442f-af56-4fd5475b3818.png)

   
   - On a users profile, they have a button that allows them to add posts as well as having and edit and delete button besides all of their posted theories.

### First Time visitor goals 

 "As a first time user, i want to be able to create an account quickly and securely."
 
  - Upon arriving to the site, a browse button is just bellow the hero summary which either takes registered users to the browse page, or new visitors to the registration page.    This allows users to easily become members without any hassle.
  - Also, the navigation bar has a link to the registration page which is a simple form for the user to fill out, once completed, they are taken to their profile page.
  
  ![Untitled](https://user-images.githubusercontent.com/75024926/130271854-d8aa4296-972e-4f23-a609-ec0a6ca35703.png)
  ![Untitled](https://user-images.githubusercontent.com/75024926/130271935-dbfb1123-1b18-4fb9-824e-1efbdb8839a9.png)
  
  ### Returning visitor goals 
  
  "As a returning visitor, i want to be able to serach the site for theory that i want."
  
  - Once a user has logged in, either through the navigation bar or on the landing page, their are links to take them to the browse page. At the top of the page, a search bar is visible mand they are able to search through the community posts. The results are filtered through the theory name and description.

![Untitled](https://user-images.githubusercontent.com/75024926/130273811-4d4db323-5282-45d6-b605-f348191f0dd5.png)

  ### Accessibilty
  
  [Screenshots from Google Lighthouse's accessibility checker can be viewed here]()
  
  












 
 

  
  

  
