# Investpal
![image](https://github.com/Yonaseyob/investpal/assets/112119971/ed1c04e1-24f2-4bb6-aac2-74e2a5b76345)


Investpal is a blog website dedicated to providing information about small business ideas around the world for users.

# User Experience
### Agile

I implemented agile methodology when creating this website. The link to the project board can be found https://github.com/users/Yonaseyob/projects/8/views/1

### User Stories

### Home Page not logged in

- As a user I want to be able to tell what the website is about.
- As a user I want to see the posts.
- As a user I want to be able to register.
- As a user I want to be able to login. 
- As a user I want to be able to see the likes and dislikes.
    
Home page logged in
- As a user I want to be able to add a post.
- As a user I want to be able to logout.

Admin Page

To access the admin page type <strong>/admin</strong> at the end of the address bar
- As an admin I want to be able to add posts.
- As an admin I want to be able to approve or not approve posts.
- As an admin I want to be able to approve or not approve comments. 

Register

- As a user I want to be able to register.

Login Page

- As a user I want to be able to login with username and password.
- As a user I want to have the option of remembering me indtead of having to login.

Logout Page

- As a user I want to be able to logout.


## Features 

### Existing Features

- __Navigation Bar__

   ![image](https://github.com/Yonaseyob/investpal/assets/112119971/e60d860d-9a70-4f02-a0f4-e0106c3e226f)

  - Featured at the top of the page, the full responsive navigation bar includes the blog name, Home page on each page to allow for easy navigation, register, log in, and add logout depending on if the user is logged in.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert to the previous page via the ‘back’ button. 

- __The Home page__

   ![image](https://github.com/Yonaseyob/investpal/assets/112119971/db4fce90-b122-4459-8b40-e3759c2d3e3a)

  - The home page includes information about the webpage and the posts on the blog by the admin.
  - By clicking the post title the registered user has the ability to read and comment on the posts.

- __The Footer__

  ![image](https://github.com/Yonaseyob/investpal/assets/112119971/e9582071-47b8-4fc5-a0cc-13245d35a700)

  - The footer section includes links to the relevant social media sites for Investpal. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

- __The Sign Up Page__

   ![image](https://github.com/Yonaseyob/investpal/assets/112119971/e30ff47e-5481-415f-b10a-637b42bbd25b)

  - This page will allow the user to get signed up to Investpal to read and comment on posts. The user will be asked to submit their name.

- __The log in page__

   ![image](https://github.com/Yonaseyob/investpal/assets/112119971/d7ceae99-03d6-4ba0-8a8f-068c12cb7151)

  - The login page has a form from Django Forms that allows users to log in to their account.

 - __The logout page__

   ![image](https://github.com/Yonaseyob/investpal/assets/112119971/05bdd507-9bc9-4d4a-9d93-c8cb49658147)

   - The logout page shows the user a message if they are sure to log out with a confirmation signout button.

- __Add Posts__

   ![add post](https://github.com/Yonaseyob/investpal-blog/assets/112119971/695e6699-ed3e-453c-b5f0-4d6df5ce3a32)

   - The post page displays the post.
   - The post has an image that the author of the post chooses to upload.

   When user is logged in
     - The post has two buttons underneath displaying the likes and dislikes.

        ![post](https://github.com/Yonaseyob/investpal-blog/assets/112119971/8a1973a1-4afc-411d-9caf-2fc8cc002711)

   When user is author of the post
    - Two buttons display if the user is the author of the post.
    - An edit button is displayed if the user is the author of the post.
    - A delete button is displayed if the user is the author of the post.
 
### Features Left to Implement

- I would like to expand the blog page to be more interactive for the users to be able to connect each other.

 ### Technologies
 
- __Languages used__
 - HTML 
 - CSS 
 - JavaScript 
 - Django libraries 
- __Frameworks, Libraries, and Programs Used__
  - Codeanywhere, for editing the code
  - GitHub, used to host the project.
  - Heroku, To deploy the webpage.
  - ElephantSQL, as a database
  - Cloudinary, as media and image host


## Testing 

### Manual Testing
.
  - Google Chrome no appearance, responsiveness or functionality issues.
  - Safari no appearance, responsiveness or functionality issues. 
  - Microsoft Edge no appearance, responsiveness or functionality issues.
  - Firefox no appearance, responsiveness or functionality issues.

### Device compatibility

  - I tested the blog website on my laptop and phone by adding a post after deployment on Heroku and it works like what I expected.

 ## Test cases
 ### Navigation Bar Not logged in
 
  - Clicked on Home in navigation bar.  It refreshed the page. 
  - Clicked on register in navigation bar. It went to the registration page.
  - Clicked on Login in navigation bar. It went to the login page.

 ### Navigation Bar<strong> (Logged in)</strong>
    
  - Clicked on Home in navigation bar. It refreshed the page. 
  - Clicked on the navbrand in navigation bar. It refreshed the page.
  - Clicked on Add a Recipe in navigation bar. | It went to the add a recipe page.
  - Clicked on Logout in navigation bar. It went to the logout page.

 ### Footer Bar
 
  - Clicked on Twitter icon. It opened twitter in a new page.
  - Clicked on Facebook icon. It opened facebook in a new page.
  - Clicked on Instagram icon. It opened instagram in a new page.

 ### Index Page
 
   - Clicked on Post on index page. It went to the Post page.
   - On Login. recieves notification that I was signed in.
   - On Logout. recieves notification that I was signed out.

 ### Add a Post Page Logged in
 
  - Added a post on add a post page. Recived notification that post is submitted for approval. 

 ### Post Page Logged in
 
  - Clicked on like(heart icon). The number of the likes went up.  
  - Clicked on dislike(thumbs down icon). The number of the dislikes went up. 
  - Wrote a comment. Recieved notification of comment is awaiting approval. 

### Validator Testing 

- HTML W3c validater.
  
  - I found three errors acording to the validater but according to the walkthrough project I did not make any changes.

    ![html](https://github.com/Yonaseyob/investpal-blog/assets/112119971/d01045d4-bddd-4aa9-a067-958e8b2f1a70)

- CSS W3c validater.
  
  - No errors were found when passing through the official W3c validater.

   ![image](https://github.com/Yonaseyob/investpal/assets/112119971/8b7150b0-55ac-4dc2-bc6b-763669a061db)

- Python validater.
   - No errores found.

   - Admin.py

      ![Admin py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/a4f48bdf-41f1-4c36-a0b0-40f3a2bfb359)

   - Forms.py

    ![forms py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/7ba47095-ea27-4856-8836-aac8133e4e64)

   - models.py

    ![models py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/98c77fc9-df03-453b-8d9b-db5614d35cd4)

   - Blog urls.py

     ![blog url py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/345d7b26-a00d-4acd-af91-0d3ff5e8f5ca)

   - Views.py

     ![viwes py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/894dbdfe-e43d-4a20-9f66-decec95ec9eb)

   - Settings.py
     
     ![settings py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/8c8e8d91-62ca-43d5-8b3d-70f48e462430)

   - Investpal2 urls.py
     
     ![investpal2 url py](https://github.com/Yonaseyob/investpal-blog/assets/112119971/281380b3-ce29-4896-b401-e631074a2d04)
     
## Lighthouse

   - Home
     
     ![LH home](https://github.com/Yonaseyob/investpal-blog/assets/112119971/6bb6b73f-4470-4c0e-882f-bc0397859b82)

   - Sign up

     ![LH sign up](https://github.com/Yonaseyob/investpal-blog/assets/112119971/5606a7aa-b148-4618-8c2e-7dbfcf5e7003)

   - Sign in

     ![LH sign in](https://github.com/Yonaseyob/investpal-blog/assets/112119971/1faff72c-73af-40d8-b442-c7c445de03ad)

   - Add post

     ![LH add post](https://github.com/Yonaseyob/investpal-blog/assets/112119971/5a121b85-0961-49d3-b330-37ba2cd1c9d9)


### Unfixed Bugs

  - Not found any

## Deployment

  - The site was deployed to Heroku. 
  - In the Heroku dashboard navigate to the deploy tab 
  - From the source section drop-down menu, select the Main Branch and clike the deploye button.
 
The live link can be found here  https://investpal2-96a993dc0a64.herokuapp.com/

## Credits 

The general structure and implemented codes are adopted and reused from the code institute walkthrough project. 

### Content 

- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the posts are from google image

