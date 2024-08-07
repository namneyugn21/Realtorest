# **Realtorest**
A small web application used to host a website. Designed for hosting a personal website for realtors. Exploration, sorting, and direct contact functionalities are available for visiting users, while enabling Admin to manage listings and engage with potential buyers effectively, all within a user-friendly, ad-free environment.

### Disclaimer
Realtorest frontend and database used to be hosted on Render, however, we (as university students) do not have unlimited funds that can keep the database to be hosted forever. <br>
I have tested and wrote the instructions below, but if there is something coming up during the process, kindly reach me at: vhn1@sfu.ca

### How to run the application
1. Running `PostgreSQL`: <br>
- Make sure you have `PostgreSQL` running on your computer, and create a database `realtorest`.
- You can create the tables by copy and paste the code provided in `PostgreSQLCode.txt` file.
- Make sure to enter your `PostgreSQL` credentials in the `application.properties` file.
2. Adding `Google Maps API`: <br>
- If you want to add `Google Maps API` key, please navigate to `PropertyController.java` and add your key on `line 60`.

### Port ID
The port when deploying this project to `localhost` have been changed to `9090`.

### Admin Pages
The admin pages can be accessed by going to `/dev`, `/dev/users`, `/dev/properties`, and `/dev/admins`. It have some useful functions, like displaying the table of all users and adding users manually. Those pages will be disabled in the final product, but while developing, they are pretty useful.

### Password Reset
The Mailgun API only allows for sending emails to 5 pre-authorized accounts if you don't pay. So it may be impossible to receive the password reset email. 

It may be a good idea to register for a Mailgun Account and use your own credentials for this.

## About this project
### Abstract
**Realtorest** is a real estate web application that is created for a realtor. The application displays a list of properties that can be sorted based on price, location and room features, and the available map feature can assist users to explore properties in different locations. From general users’ perspective, users can create an account, manage their basic information, control their property choices with features such as ‘Save as Favorite’, and connect with the website owner to discuss or set up an appointment. The application is specifically tailored for our client, who is the middleman that helps property sellers and buyers connect with each other. This application focuses on helping the client upload and display information of properties that are being sold and help potential buyers who are interested in those properties to make the purchase.

### Project Description
Our client is a realtor in British Columbia who does not have a personal website for their real estate business, and due to the competitiveness in the industry, a personal website can benefit our client a lot by helping them connect with potential clients and widening their business scope. Hence, the web application **Realtorest** is created to help our client connect to property buyers and sellers. The description will outline two types of users that will use this software: the project’s client, who will be the admin of the website. And the general customers, who are home buyers, real estate investors, renters, and real estate professionals. Detailed below are the high-level descriptions of the features that **Realtorest** has to offer.   

General customers can explore properties without the sign in but must register to contact the client or to save the properties to the favorites. Sign up/sign in  can be done using email or through third party accounts like Google. This process will save log in details in the database to avoid scam and enable property tracking. The website will also offer filters for location, room numbers, and sorting by price or distance.

**Realtorest** also utilizes application programming interface (API) for property listing view, which allows customers to view properties as markers on a map; this process requires an external API, for example Google Maps, in order to function. Moreover, customers who wish to get updated frequently about real estate news by the website owner also can sign up to be in the automated mailing list that uses an external API allowing the admins to send the update emails automatically. 

As for the Admin, they will be able to login to their website under admin login, which allows them to manage the property listing, by uploading new properties information or removing any properties that they wishes to. In addition, the website owner can get notified by any customers who are wishing to contact them regarding a property.

### Project Competitiveness
There are many personalized websites tailored for realtors, hence it is very competitive for the project to have its own distinctive features that stand out from the rest of the other websites. However, **Realtorest** is different from many other realtor websites in which it does not have any advertisements, because the project is focused on the client, rather than profit like the others. In addition, under UI perspective, most of the realtors websites that the team encountered are usually very hard to navigate and not user friendly, since there are many website features and interactions that all appear at once. Hence, to avoid this problem, **Realtorest** will focus on the customer interaction experience by creating a minimalist layout that can help the user to navigate with ease, while also providing sufficient features. 


## Screenshots
### Home Page
![Home Page](<Documentation/Screenshots/I2 Home Page.png>)
### Properties Listing
![Properties Listing View](<Documentation/Screenshots/I2 Listing.png>)
### Login
![Login](<Documentation/Screenshots/I2 Login.png>)
### Admin Login
![Admin Login](<Documentation/Screenshots/I2 Admin Login.png>)
### Register
![Register](<Documentation/Screenshots/I2 Register.png>)


## Members
### Kevin
GitHub: https://github.com/kzcheng
 
### Nam
GitHub: https://github.com/namneyugn21

### Drishty
GitHub: https://github.com/drishty02

### Amrit
GitHub: https://github.com/htoor1999

### Malaika
GitHub: https://github.com/MalaikaQ


## Documentation
### Requirements and Specification Document
https://docs.google.com/document/d/1M230-rUDm0COryomhOioVhkQSJLFG93NoL5_G9oMAYM/edit?usp=sharing


## Useful Links
### GitHub Repository
https://github.com/CMPT276-Project-Group-6/Realtorest

### GitHub Organization
https://github.com/CMPT276-Project-Group-6
