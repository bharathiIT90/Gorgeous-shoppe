# GorgeousShoppe.com
Know more about the developer on <a href="https://www.linkedin.com/in/bharathi-ranganathan">Linkedin</a>

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [REST API Testing](#rest-api-testing)
- [Exploration](#exploration)


## Introduction

A full stack online shopping web application which allows user to select their desired product, make payment and checkout. When the user logs into the application, they are able to choose the products from a list of products. The products are grouped according to various categories. The user is allowed to apply filters and make their selection. The application allows both guest user and registered user for checking out. The user also has freedom to choose a product from various options under each product. 

## Features
### Current Features
1. Product selection according to different product variation. <br/>
2. Quantity selection and cart updation accordingly. <br/>
3. Tax, shipping and order total calculations. <br/>
4. Product category and price range filters. <br/>
5. Guest User and registered User login. <br/>
6. User Address and payment options. <br/>

### Future Enhancements
1. Improving the front end UI by showing flashy product promotions that change every few seconds. <br/>
2. Updating the product view to display different images for every product variations provided. <br/>

## Technologies
Python, Django framework, sqlite3, AJAX, Jquery, HTML, CSS, Bootstrap, Braintree for payment, Jquery flash messages, Django REST framework.

**Front-end**
HTML, custom CSS paired with bootstrap is the main part of the Front end. Flash messages for the cart update is run through Jquery. 

**Back-end**
Python runs the back end of GorgeousShoppe. Django web framework is used to create relations between different applications and databases. AJAX is used for querying the database to update the cart quickly once the quantity and product is updated. Braintree is used for providing payments options using paypal and credit card. 


## REST API Testing 
1. Created a cart.
2. Created a Json cart token.
3. Generated new url and checkout url using Json token.
4. An arbitary email is passed as argument in the test case function.Requested address from the user.
5. Returned the addresses related to user checkout if addresses already available.
6. Created an arbitrary user_id.
7. Updated the checkout url to produce the order details of billing address, shipping address and cart and checkout token.

## Exploration

Homepage:

![image](https://cloud.githubusercontent.com/assets/16948906/17043326/828485ae-4f6a-11e6-95f1-43b187c862a9.png)

CartView:

<img width="1259" alt="cartview" src="https://cloud.githubusercontent.com/assets/16948906/17046550/83a5df72-4f89-11e6-867f-826ce5adba58.png">

Guest/ Registered-user login:

<img width="1263" alt="guest login" src="https://cloud.githubusercontent.com/assets/16948906/17046606/0f5e9126-4f8a-11e6-963b-e88569b6409f.png">

Product Categories/Filter:

<img width="1259" alt="filters" src="https://cloud.githubusercontent.com/assets/16948906/17046608/11079d24-4f8a-11e6-9dba-04c3071fe4db.png">

Order Summary:

<img width="1259" alt="ordersummary" src="https://cloud.githubusercontent.com/assets/16948906/17046609/1290ea56-4f8a-11e6-8a25-8b7b39fbbcb6.png">
