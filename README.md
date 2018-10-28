Project Developed By - Team Dementors

Project Name - 'J A A T R A'

Project Introduction - 

'J A A T R A' is an online bus ticket booking system. 
We have connected with over 20 bus enterprises all over Bangladesh to provide you with tickets at your doorstep.
'J A A T R A' offers you the option to pay through your VISA, mastercard and bkash account! 
We will also be integrating cash on delivery payment service in the near future.

![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/jaatraLOGO.jpg "jaatraLOGO")

Admin Sign In-
![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/signIn.PNG "Signin View")


Homepage -

![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/JaatraHome.PNG "Home Page Image")

![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/JaatraHomeTwo.PNG "Home Page Image")


Ticket Search -
![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/jaatraticketSearch.PNG "Ticket Search")

Customer Information-
![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/customerInfoPage.PNG "Customer Information Page")

About Section-
![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/JaatraAbout.PNG "About Section")

Contact Section-
![alt text](https://github.com/iub-cse-shq/jaatra/blob/master/public/images/jaatraContact.PNG "Contact")



**How to set up the code**

1. Install [Node.js](https://nodejs.org/en/download/) and [MongoDB](https://www.mongodb.com/download-center?jmp=nav) on your computer

2. Download this code, and from command prompt run:

   `npm install`


   `bower install`


3. To run the code, run:

    `node server.js`

    
4. In the browser open http://localhost:3000/, and you should see the index page

**Exposed APIs**:

GET **/api/articles** (returns list of articles)

POST **/api/articles** (create new article)

GET **/api/articles/:articleId** (returns an article with matching id)

DELETE **/api/articles/:articleId** (deletes the matching article)

GET **/api/articles/edit/:articleId** (returns an article with matching id)

PUT **/api/articles/edit/:articleId** (updates the matching article)
