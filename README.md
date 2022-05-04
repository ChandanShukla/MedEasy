# CSCI5709 Project - Advanced Topics in Web Development

# (MedEasy Application - Group 18)#

# MedEasy Objective
* The primary goal of our Web application, Med Easy is to make it easier for the public to order medicines and other medicinal equipment remotely – online, by becoming a one-stop-shop to all thing’s pharmacy. While there are several pharmacies deployed everywhere, there are still places where these medical stores are not always accessible. For example, there might be a medical store nearby, but it might not be open during some hours and not everyone is expected to be able to physically go to the store and pickup their medicines. This is especially true in today’s pandemic plagued world where social distancing and isolating have become the new normal.  

* To tackle these kinds of scenarios and make the pharmacy much more accessible to everyone, we have come up with the idea of Med Easy. For the first phase of our application, we are targeting the most essential features to be readily available for the users and then in the later stages of our application we can improve the scope of our project depending upon the feasibility. 

* Date Created: February 10, 2022
* Last Modification Date: April 7, 2022


# Group 18's - Git Details (this would be group repo links)  # 
* Group 18 Repository NAME:  CSCI5709_Group18
* Group 18 Repository GIT LINK (Main Branch): https://git.cs.dal.ca/ngoswami/csci5709_group18
* Group 18 Deployment Link for Heroku: https://medeasy-group18.herokuapp.com/


### Authors
* [Chandan Shukla](chandan.shukla@dal.ca) - *(Developer)*
* [Jainesh Desai](jainesh@dal.ca) - *(Developer)*
* [Aditya Busam](aditya.busam@dal.ca) - *(Developer)*
* [Dhruv Soni](dh554152@dal.ca) - *(Developer)*
* [Neelay Goswami](neelaygoswami@dal.ca) - *(Developer)*
* [Saloni Raythatha](sl768578@dal.ca) - *(Developer)*

### Instructor
* [@gmosqueraj](https://github.com/gmosqueraj)

### Teaching Assistants
* Hari Arunachalam [(@haria)]
* Nikunj Goenka [@goenka]
* Shehzeen Huda [@shehzeen]
* Yash Jaiswal [@yna]
* Bala Sundeep Krishna Dasar [@bdasari]
* Kshitij Paithankar [@paithankar]
* Neharika Sehgal [@nsehgal]
* Gurleen Saluja [@gsaluja]
* Ana Khan [@anan]
* Mansi Singh [@mansis]


**Below is the demo/sample user for testing our application**
<pre>
For testing Search Box functionality it is not needed but for other features, you can use as below:
Normal User
email: testuser@gmail.com
password: Test@123

Admin User
email: testadmin@gmail.com
password: Test@123

Payment Card details:
Card No: 4242 4242 4242 4242
Card Expiry: 12/34
Card Cvv: 123
Name on Card: Any
Pin Code: Any
</pre>


## For the Backend part of our project, it communicates with Frontend using APIs. ##
* models - all the application-related common models.
* controller - controller for all the features.
* routes - routes/API's.

## For the Frontend part of our project it is divided as below: ##
* containers - all features are located in the container (for instance my feature SearchResults can be found there) accordingly to everyone else's as well. 
* components - all components for eg. Header, Footer, Layout many more can be found here.


### For Frontend of our Application
* [ReactJS](https://reactjs.org/) - Javascript library for UI
* [react-bootstrap](https://react-bootstrap.github.io/) - Used to incorporate bootstrap components to style our parts.
* [axios](https://www.npmjs.com/package/axios) - Communicaiton of Backend with API and fetching the data.

### For Backend of our Application
* [NodeJS](https://nodejs.org/en/) - Node JS learning for our application
* [Express](https://expressjs.com/) - Express learning for our application

### For Database
* [MongoDB] (https://www.mongodb.com/) - NoSQL Database for data storage


## Sources Used to learn and understand some functions related to react
* Online sources like "https://reactjs.org/docs/create-a-new-react-app.html" have been used to revisit some of the commands to make a react app and run on local machine.
* To understand the usage of function and class component for react - https://www.twilio.com/blog/react-choose-functional-components
* For styling/css - https://www.w3schools.com/css/
* All other react functionalities - https://reactjs.org/
* Some of the code for validation and functionalities was used for reference purposes from our group proposal and previous assignments from the class. 
* Clone the project at your local. Choose IDE like ATOM/Intellij to open the cloned project.

## Feature - Checkout and Payment

I have taken the feature of checkout and payment to be developed for the Assignment 3 task. I have designed the payment feature for the MedEasy application which i have integrated with the stripe payment interface. I have created the Checkout Page where the user fills in the shipping details, then user click on place order. On the Payments page there is information for billing address after which the user can select the payment type. Currently there is only one payment type that is credit/debit card. Once we click on the place now button, you gets redirected to the Stripe checkout session where the user need to fill in the card details(test card) that are provided below. Once the user fills in the details the mandate details and click place order then it get validated from the stripe end and then you get redirected to order placed page. On the Success order place page there is option to view order details, once the user click on the order details button then, it get redirected to Order Details page where he will be able to see his orders. 

pre condition - user must be logged in
card number - 4242 4242 4242 4242
expiry date  - 1234
cvv - 123

name - any name you can add
Zipcode  -  6 digit number

## files developed by me for the front end application

Below are the various folder and files that arepresent inside the Frontend folder that is present inside the root directory

*   Folder - [/Frontend/src/components/Footer/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/Footer)
    Footer.jsx
    Footer.css

*   Folder - [/Frontend/src/components/Header/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/Header)
    Header.jsx
    Header.css
    
*   Folder - [/Frontend/src/components/HeaderNew/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/HeaderNew)
    Header.jsx
    Header.css

*   Folder - [/Frontend/src/components/Layout/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/Layout)
    Layout.jsx
    Layout.css
    
*   Folder - [/Frontend/src/components/NavElements/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/NavElements)
    NavElements.jsx

*   Folder - [/Frontend/src/components/PageTitle/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/PageTitle)
    PageTitle.jsx
    
*   Folder - [/Frontend/src/components/Topbar/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/components/Topbar)
    SideBar.jsx

*   Folder - [/Frontend/src/containers/NewCheckout] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/containers/NewCheckout)
    Checkout.jsx
    Checkout.css
    
*   Folder - [/Frontend/src/containers/OrderDetails] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/containers/OrderDetails)
    OrderDetails.jsx
    OrderDetails.css
    
*   Folder  - [/Frontend/src/containers/OrderPlaced] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/containers/OrderPlaced)
    OrderPlaced.jsx
    OrderPlaced.css

*   Folder - [/Frontend/src/containers/Payment] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/containers/Payment)
    Payment.jsx
    Payment.css

*   Folder  - [/Frontend/src/features/payment] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/features/payment)
    PaymentAmount.js
    PaymentType.js
    
*   Folder - [/Frontend/src/app] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src/app)
    store.js
    
*   Folder - [/Frontend/src/] - (https://git.cs.dal.ca/ngoswami/csci5709_group18/-/tree/main/Frontend/src)
    app.js
    index.js


## Files developed by me for the backend application

*   Folder - [/Backend/controllers]
    orderController.js
    stripePaymentController.js
    
*   Folder - [/Backend/db]
    connect.js

*   Folder - [/Backend/models]
    orderModel.js
    
*   Folder - [/Backend/routes]
    orderRoute.js
    stripePaymentRoute.js
    
*   Folder - [/Backend/]
    App.js
    Server.js


## Code Integration

Checkout and Payment module was directly dependent on the cart management modeule and user management module. As only the registered user must be allowed to place the order by paying for the goods cost. At the same time if there would be no item in the cart then user cannot buy any product. I have actively collaborated with the team members who were working on these modules for a smooth integration experience. Overall worked with the team to develop the common elements that were used throughout the website. Finally we have intergated the code, build our react application and then deployed our final application on the Heroku platform.

## Tools and softwares used

* [React] (https://reactjs.org/) - Frontend framework
* [Heroku] (https://dashboard.heroku.com/login) - Cloud platform to deploy application
* [Express] (https://expressjs.com/) - Web framework for Nodejs
* [Postman] (https://www.postman.com/) - API testing software
* [MongoCompass] - Tool used to check the collections and data on the database
* [MongoDB] (https://www.mongodb.com/) - NoSQL Database for data storage
* [NPM] (https://www.npmjs.com/) - Nodejs package manager
* [Nodejs] (https://nodejs.org/en/) - Backend Javascript Runtime
* [VS Code] (https://code.visualstudio.com/) - IDE used for development
* [Gitlab] (https://git.cs.dal.ca/) - Repository and version control system
* [Microsoft Edge] (https://www.microsoft.com/en-us/edge?r=1) - Browser of choice for testing frontend changes


## Sources Used

### NaveElements.jsx
<pre>
export const Nav = styled.nav`
    background: linear-gradient(to right, #1A374D , #11999E 60%, #E4F9F5);
    height: 60px;
    display: flex;
    justify-content: space-between;
    padding: 0.5rem cacl((100vw - 1000px)/2);
    z-index: 15;

    @media screen and (max-width: 1200px){
        transition: 0.8s all ease;
    }
`

export const NavBrand = styled(Link)`
    color: #fff;
    display: flex;
    align-items: center;
    text-decoration: none;
    padding: 1.2rem;
    height: 100%;
    cursor: pointer;
    margin-left: 0.5rem;
    font-size: 25px;
    &.active{
        color: #fff;
    }
`

export const NavLink = styled(Link)`
    color: #1A374D;
    display: flex;
    align-items: center;
    text-decoration: none;
    padding: 0.5rem;
    height: 100%;
    cursor: pointer;
    margin-left: 0.5rem;
    &.active{
        color: #11999E;
    }
    &:hover {
        color: #11999E;
        border-bottom: 3px solid #147581;
      }
`

export const SideBarMenuWrap = styled.div`
  color: #11999E;
`;





export const SideBarLink = styled(Link)`
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 3rem;
  text-decoration: none;
  list-style: none;
  transition: 0.2s ease-in-out;
  color: #E4F9F5;
  cursor: pointer;
  
  &:hover{
    color: #11999E;
    background: #E4F9F5;
    transition: 0.2s ease-in-out;
  }

`;



export const SideBarMenu = styled.div`

  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: repeat(6, 80px);
  text-align: center;
  
  @media screen and (max-width: 480px) {
    grid-template-rows: repeat(6, 60px);
  }
  
  
`;
</pre>
Utilised these to build the responsive navbar, it was an efficient code and the end result was great. I have modified this code as per our applications requirement


* Material UI Grid - https://mui.com/components/grid/
* Material UI Stack - https://mui.com/components/stack/
* Material UI Paper - https://mui.com/components/paper/
* Material UI Box - https://mui.com/components/box/
* Material UI Accordion - https://mui.com/components/accordion/
* Material UI TextField - https://mui.com/components/text-fields/
* Material UI Radio button - https://mui.com/components/radio-buttons/
* React NavBar - https://www.youtube.com/watch?v=VzWBLj_CfpE&ab_channel=BrianDesign
* Stripe Payment API - https://stripe.com/docs/api


# Getting Started with Create React App
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


### Prerequisites  
* Gitlab as code management repository.
* Heroku CLI for deployment.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


## Running application locally

* Clone the git repository 
  ```
  $git clone https://git.cs.dal.ca/ngoswami/csci5709_group18.git

* Open with Visual Studio or any preferrable ide. 


## Built With
  
* [React](https://reactjs.org/) - Frontend framework
* [Node](https://nodejs.org/) - Backend JavaScript runtime built on [Chrome's V8 JavaScript engine](https://v8.dev/)
* [NPM](https://www.npmjs.com/) - The package manager for  
* [Node](https://nodejs.org/)
* [GitHub](https://github.com/) - The version control tool
* [Visual Studio Code](https://code.visualstudio.com/download) - The source code editor used
* [Google Chrome](https://www.google.com/intl/en_in/chrome/) - Browser used to visualize the changes
* [Heroku](https://dashboard.heroku.com/) - The cloud platform used for our application deployment


## Citation for all the images used from online

1. Surgical Mask = https://www.amazon.in/Disposable-Surgical-FABRIC-Earloop-Certified/dp/B096B99BDW
2. Thermometer = https://www.amazon.in/Dr-Trust-Waterproof-Flexible-Thermometer/dp/B07GSRD84M
3. Metacin = https://www.apollopharmacy.in/otc/metacin-tablet
4. Ibuprofen for kids = https://www.heb.com/product-detail/h-e-b-children-s-ibuprofen-100-mg-oral-suspension-bubble-gum-flavor/483094
5. Iburpofen Advil = https://www.tradeindia.com/products/ibuprofen-tablets-c6749541.html
6. Azithromycin = https://zeenews.india.com/health/azithromycin-potential-covid-19-drug-may-increase-risk-for-cardiac-events-2310378
7. Baby Wipes = https://www.amazon.in/Littles-Soft-Cleansing-Baby-Wipes/dp/B004X7545M
8. Blood Pressume Machine = https://www.tradeindia.com/manufacturers/digital-blood-pressure-monitor.html
9. Cough Drops = https://www.metromarket.net/p/kroger-honey-lemon-cough-drops/0004126037077
10. Crocin = https://www.lybrate.com/otc/crocin-cold-flu-max-tablet
11. Band Aid = https://www.band-aid.com/products/adhesive-bandages/skin-flex-bandages
