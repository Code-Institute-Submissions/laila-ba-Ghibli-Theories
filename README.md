# Ghibli Theories

![Untitled](https://user-images.githubusercontent.com/75024926/130273638-6c406986-ad01-4d31-a128-f7939f44728c.png)


# About

Ghibli Theories is a website that focuses on bringing Studio Ghibli fans a simple and easy platform to share and learn about new Ghibli-based theories. Its main purpose is to keep fans up to date with the latest news and stories while allowing users to post, edit and delete their posts. 

# User Experience
## User stories
- Common User Stories
  
  a. I want to find using the website's functionality simple with clear clear navigation.

  b. I want the site to be responsive on all screen sizes.

- First-time visitor Goals
  
  a. I want to be able to create an account quickly and securely.

  b. I want to be able to find the 'Register' page easily.
  
- Returning visitor Goals

  a. I want to be able to search the site for the theory that I want.
  
  b. I want to be able to navigate to the 'Login' page easily.

  c. I want to post new theories easily.

  d. I want to have full control of my created posts following computer programming CRUD (create, read, update & delete) operations.

  e. I want to view all posts that were created by me.

  f. I want to be able to Log out.
 
  
  # Design

  ## Color Scheme

- I wanted to create a fun and colorful color scheme,which co ordinates with Ghibli films, while still keeping the site looking simplistic and clean. Because of this, i chose to stick to only two main colors that are based on the hero image on the landing page. It contains tones of royal blue and orange. Throughout the whole site, I have chosen to use dark blue, orange, and green. These fun colors stand out nicely against white backgrounds without appearing too much on the eye. They also portray the fun and magical feel that the Ghibli films offer to their fans.

  <img src="readme-docs/color-scheme.png">

- Dark navy blue (#1d438a) - This is one of the main primary colors of the site used alongside orange. It goes well with the website as it carries on the deep-sea theme that the hero image on the landing page conveys. It is used for: banners of information and image titles for ghibli posts.

- Coral Orange (#f4623a)- Taken from the hero image, this coral color is adapted a lot more throughout the site, being the primary color across the project. The contrast between blue and orange works nicely and goes hand in hand. It's used for: the logo, dividers underneath titles, URL buttons, hovering over nav sub-pages, and community post titles

- Green (#008000) and Red(#ff0000)- A hint of green and red are used on the profile page for the edit and delete buttons to stand out to the user as both buttons allow the user to manage their data.

## Typography
 There are two fonts used throughout the site: "Merriweather" and "Merriweather-Sans"

  <img src="readme-docs/typography.png">
 
 - I wanted to use a combination of two fonts to not make the site boring and plain. "Merriweather-Sans" I used for big title texts and buttons as it's slightly thicker and bolder, whereas "Merriweather" is used for the text on posts and larger quantities of information.

## Imagery

- Images appear the most on the landing page to attract and show the site's visitors what the focus of the website is. Using high-quality images from Ghibli films keeps the ghibli aesthetic strong and attracts more users to the site, ultimately converting them into registered, active users. Images such as the hero image are used on the landing page, log in, logout, add and edit pages to keep the pages exciting and not bland.



  ## Scope
  
  Features within the initial design:
  
  - A fully responsive website, can be viewed on any device.
  
  - buttons on the landing page persuading the user to browse theories and register
  
  - allowing users to create and manage their accounts
    - This includes editing and deleting their posts.
  
  - registered users can search the browse page for theories.

  - My site will include sub-pages such as Home, Browse, Add, Profile, login, logout, register
    - subpages such as browse, add, profile, and login will only be available to registered users that are signed into their account.
  
  - Once a user adds a theory and posts it, it is visible to the community on the browse page.

  - The browse page will include a section for theories posted by the web site's creator and another section posted by the community.

  ## Structure
  
  #### Navigation Bar 
  
   - The navigation bar will be simple and easy to use that turns into a hamburger menu when viewed on a small screen.
   - When the hamburger menu is clicked, a dropdown menu appears with the subpages. When the dropdown menu appears, the content below moves down allowing no content to be hidden underneath the navigation bar.
 
 #### Landing Page 
 
   - A vibrant hero image with the website name will appear in big bold writing with a short and simple summary below. A button will be placed below for 'Browse Theories' to allow easy navigation. For unregistered users, this takes them to the register page and for registered users, this takes them to the browse page.
    
   - Below the hero image, a small section will appear with the title 'join the community and a register button, again, for easy navigation while making the signing up process easy and simple for the user.
    
   - There will be a 'sneak peak' section with a small number of theories that draw new users to the site and allows them to see what the website is all about. The theories that appear in this section are posted by the website creator.
     - When these are clicked on, a larger page appears with an enlarged image and text for the user to easily read. There is a close icon at the top of the page and a close button at the button.
      
   - Underneath this area, there is a small section with the title of 'want to see more?' that redirects users to the register page. The redirects to the register page persuade the user to signup to have full access to the website without any hassle.
    
  #### Browse Page 
  
  - At the top of the browse page, there will be a search bar that will enable the user to search through the communities posts, the results will be filtered through the theory names and descriptions. Besides this is a 'clear' button allowing the search bar and results to be reset. 
  - section below will be the theories that are posted by the website's creator which have a clear difference in styling.
  - When viewed on mobile, The posts appear on top of each other rather than beside each other, making it easier and more efficient to view on smaller devices.
  - The browse page is only visible to registered users so that posts are only seen within the community.

#### Login, register, add post, edit post 

  - The forms used on these pages are all the same, keeping the same aesthetic throughout the website.
  - The add and edit forms can be only be accessed by registered users.

#### 404

- A custom 404 error page for when a user tries to access a page that doesn't fit their current state. e.g: the user attempts to register while being logged in. The 404 page has a link that takes them back to the home page and an image that fits well with the aesthetic of the website.

#### Profile 

  - The profile page will show the user's username alongside their posts while also giving them an option to add a post. Each of their posts will have an option to edit and delete. If the user chooses to delete the post, a modal pop appears asking the user again if they want to delete it. This is added for precaution just in case the user has clicked delete by accident. The profile page follows CRUD operations as it allows users to add, edit and delete their posts easily. Once posts are deleted, they are also removed from the browse section and will no longer be visible to the community
  - When posts are added, edited, or deleted, flash messages will appear letting the user know that it has been successful

## Mockups

- [Desktop webiste view](https://github.com/laila-ba/Ghibli-Theories/blob/main/mockups/desktop%20view.pdf)
- [Mobile webiste view](https://github.com/laila-ba/Ghibli-Theories/blob/main/mockups/mobile%20view.pdf)


## Database Model
For this project, I chose to use MongoDB for all database aspects to become more familiar with it through practice and development.MongoDB stores data in flexible, JSON-like documents, meaning fields can vary from document to document and data structure can be changed over time.

- Using 12-bit-MongoDB-specific unique values such as ObjectId's can be used to identify objects within the Database as it is used by MongoDB to search for a specific ObjectID.This is used within my project for my site to run smoothly, allowing users to manage their data.

![database model](https://user-images.githubusercontent.com/75024926/130251989-16ea9f50-c077-48b8-b79a-80f0abd5940f.png)

Above, we have the posts collection that contains a user's post when added and the user's collection, containing login info. Within both collections, the ObjectID is present so that the data can be manipulated and the DB can be searched.

## Future Features

- Add like and dislike buttons to users posts, allowing the community to engage with one another
- Added newsletter signup that would send registered users the latest theories by email

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
  
  Once I had finished the code for the project and put the URL into the validators, these were the main errors that appeared and how I resolved them:
  
   - "A slash was not immediately followed by >"
       " alt="close"//></div>↩"    
       - This was shown on multiple lines that had the img src for the close icon. I resolved this by removing the extra '/' on every line.
        - There were no other errors present

 #### CSS Validation 
 
  - Value Error : color Lexical error at line 3880, column 11. Encountered: "#" (35), after : "#" #00709c;
     
     - These errors were shown on multiple lines for extra hashtags for color codes. I resolved this by removing the extra tags.
      - There were no other errors present

#### JS Validation 

  - The main errors I received were missing or unnecessary semi-colons which were resolved by adding and removing them.
    - There were no other errors present

#### Python Validation

  - There were no other errors present

## User Story Testing 

"As a user, I want to find using the website's functionality simple and easy to use."

  - Users a greeted with a short and simple summary on the landing page with a link to the browse page. Through the summary, they can understand immediately what the site's focus is.
  
   ![objectID2](https://user-images.githubusercontent.com/75024926/130268776-5a903380-b7c3-4101-a4b3-966c608b3180.png)
   
   - Form input fields are clear and simple to proceed to fill it in. Users can post theories easily without hassle.
   
  ![objectID2](https://user-images.githubusercontent.com/75024926/130270215-aab87839-9656-47df-bb28-46d721948d6f.png)
  
   "As a user, I want to have full control of my created posts following computer programming CRUD (create, read, update & delete) operations."
    
   - Users have full control of their posts as they can create, read, update and delete. My project has implemented CRUD functionality for the user to manage their posts.
   ![Untitled](https://user-images.githubusercontent.com/75024926/130270915-20d24c32-9b00-485b-b205-bdc5628be3bf.png)
   ![Untitled](https://user-images.githubusercontent.com/75024926/130271151-388f0bb2-ea3b-442f-af56-4fd5475b3818.png)

   
   - On a user's profile, they have a button that allows them to add posts as well as having edit and delete button beside all of their posted theories.

### First Time visitor goals 

 "As a first-time user, I want to be able to create an account quickly and securely."
 
  - Upon arriving on the site, a browse button is just below the hero summary which either takes registered users to the browse page, or new visitors to the registration page.    This allows users to easily become members without any hassle.
  - Also, the navigation bar has a link to the registration page which is a simple form for the user to fill out, once completed, they are taken to their profile page.
  
  ![Untitled](https://user-images.githubusercontent.com/75024926/130271854-d8aa4296-972e-4f23-a609-ec0a6ca35703.png)
  ![Untitled](https://user-images.githubusercontent.com/75024926/130271935-dbfb1123-1b18-4fb9-824e-1efbdb8839a9.png)
  
  ### Returning visitor goals 
  
  "As a returning visitor, I want to be able to search the site for the theory that I want."
  
  - Once a user has logged in, either through the navigation bar or on the landing page, there are links to take them to the browse page. At the top of the page, a search bar is visible and they can search through the community posts. The results are filtered through the theory name and description.

![Untitled](https://user-images.githubusercontent.com/75024926/130273811-4d4db323-5282-45d6-b605-f348191f0dd5.png)

  ### Accessibilty
  
  [Screenshots from Google Lighthouse's accessibility checker can be viewed here](https://github.com/laila-ba/Ghibli-Theories/tree/main/testing)
  
  ### Bugs
  
  #### Listed below are some bugs I came across while building this project and how I resolved them:
  
  1. Making the forms responsive on mobile devices
    - The forms appeared nicely centered on desktop view however when the screen was smaller, the forms moved to the right and were out of view. I knew I had to add a media query to resolve the issue so I added :
      - @media screen and (max-width:522px){
          .login-page{
          width:355px;
          }
    - Through this code, I wanted to make the form's width 355px until it was viewed on a larger screen however, this didn't seem to work. I did some debugging and realized that the code wasn't being read because there was an extra '}' above the code and it was being used. Once I removed the extra curly bracket, the media query was working and the form appeared centered on smaller devices, but it was moved to the left on the desktop.

- Realizing that it hadnt worked, i then switched it around and added :

@media screen and (min-width: 522px) {
  .login-page {
    width: 500px;
  }
}

After adding this, the form was centered on both viewports and was responsive.

2. Making sure user posts were appearing fine on the browser page
  - I had an issue where the user's posts were appearing inside each other's divs. Initially, I thought there was something wrong with the styling in CSS but after taking a look at the template, I had realized that the 'end for the element was meant to be appearing between the last two divs. When doing this, the issue was resolved and the posts were appearing in their separate boxes.

![profile](https://user-images.githubusercontent.com/75024926/130280439-ffced0de-eb69-4294-8fe4-6c803e9a561b.png)

3. The search bar on the browse page didn't let users click on it to write
 - I had an issue where the search bar couldnt be clicked on, meaning something was blocking it. It took me a while to figure out however when looking at the CSS, i realised there was : pointer-events: none; being applied onto the class of the input field. Once this was removed, it was working fine.


## Deployment

Ghibli theories are live and automatically deployed to Heroku with synchronization enabled to GitHub. The env.py file, which is not sent externally, contains the necessary MongoDB information such as (IP, PORT, SECRET_KEY, MONGO_URI, MONGO_DBNAME) which allows the project to run smoothly with MongoDB. Just before deploying, carrying out a pip freeze is important as it ensures that the requirements.txt file is updated with all the necessary modules needed to deploy the app. I did this through the command 
pip3 freeze --local > 
requirements.txt
The procfile is also a very important file to be created as it is what allows Heroku to execute the app correctly. This can be done through : 
echo web: python app.py >
Procfile
Within Heroku's config vars, you must enter the information such as (IP, PORT, SECRET_KEY, MONGO_URI, MONGO_DBNAME) to link everything together.

#### Github

*Publishing*

* Within your repository section, choose which project you would like to deploy.
* At the top, underneath the project name, there are several options such as 'code' and 'issues'
* Choose the option 'settings'
* Scroll down until you see the section: 'Github Pages'
* Within this section, below 'source', choose which branch your project is under and then click Save.
* Once the page refreshes, go to the Github pages section and you will see "Your site is published at ...."
* Click on the Github Pages web address and you will see your project live.

*Forking*
You can fork a project to make a copy without it affecting the main branch with this process:

* log in to GitHub and find the repository that you wish to fork
* Once you have clicked on the repository, on the top right-hand side you will see three options: 'unwatch' 'star' and 'fork'
* Once the fork button is clicked, you will then have a copy of the repository in your Github account

*Cloning*
You can clone/download your chosen repository to your local device by using this process:

* Choose the Github repository that you wish to clone.
* Chose the 'code' button at the top next top 'add file'.
* Copy the link that you are given.
* Open your terminal and choose the directory to the location you would like the clone to be in.
* type in *git clone* and paste the URL you copied and then click enter.

## Credits

[Stack Overflow](https://stackoverflow.com/)
  - used to resolve build failure for Heroku application and application errors
  - Used to find out more information on Heroku and MongoDB

## Code

#### These are any resources that I customized and used for this project:

[Search bar](https://colorlib.com/wp/bootstrap-search-bar/)
- This was used and customized to achieve the search bar.

[Forms](https://colorlib.com/wp/bootstrap-form-templates/)
- Used for all forms across the project.

[Python Functions](https://learn.codeinstitute.net/ci_program/diplomainsoftwaredevelopment)
- Functions from the Task manager project were used as a guideline for this project.

## Acknowledgements

 A large part of this project was done independently however tutor support was extremely helpful along the way with frustrating pieces of code that would not work! That being said, I hope you all enjoy my project :)
