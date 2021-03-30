# Group-02

#  **project proposal**



                     
 ![image](https://user-images.githubusercontent.com/44206343/112887928-90766e80-90f5-11eb-9551-1f44ae3118cc.png)



                     
                     
 North South University Department of Electrical & Computer Engineering



Project Proposal 

Group No: 02 

Spring 2021 

Project Name: Milk Basket 

Course No: CSE 499

Sec: 18 

Faculty: Shaikh Shawon Arefin Shimon (Sas3)


Riaz Rahman Rafi

1620590042


riaz.rafi@northsouth.edu

Md, Shirajul Islam Shadhin

1620701042

shirajul.shadhin@northsouth.edu

Shahed Ahmed

1420308642

shahed.ahmed@northsouth.edu

Git Repository: https://github.com/NSU-SP21-CSE499-18/Group-02 

Date Submitted: 10/03/21




**INTRODUCTION**


Milk Basket is a startup-based idea which is a platform for different section of the people of the society to gather for business and welfare. It will be a website and app base platform to conjugate people respective towards their interest in the agro based products. Our headline of the project shows that it is related to milk. It will actually cover milk related periphery. It will ease the doing of business in this certain section. As there is a 6-million-ton shortage in production of milk per year in Bangladesh, our goal would be to suffice it by accelerating the process with our platform.
The intended audience would be the mass people who will be buying milk and domestic related products. The businesses who need tons of milk for their production, the farmers who need cattle feed and anyone who needs a vet for their pets and animals and lastly the investor who wants to invest in farms and share profit.


**PROPOSED FEATURES**

Below are the tentative features, 
1. There are many features to implement in this project. As it is a milk related platform and our goal is to increase the production level of milk so we have introduced several features over here like cow farm, normal user, bulk user, farm sharing, milk product, animal doctor, cow food seller. 

 2. In these features there would be some sub features to support the idea over here, like under the cow farm there would be sub features like level, rating, review, farm, photo, available time, price, providing area, about farm and location. It would create a profile for the cow farm owner. It will boost the confidence among buyers and one of the most important aspect of going digital is transparency which would meet its goal.



3. The next feature would consist of normal user and bulk user. It would have some sub feature as well like rating, review, location, photo.





4. One of the important features is going to be the farm sharing one where the investor can find their farm holders with low capitals and experience. By investing here, they can get the benefit as well like sharing profit. The main idea would be to enhance production so through this we can penetrate through the ground level as well. There will be some sub features like farm level, rating, review, location, farm size, farm photo, number of cows etc. 
5.  Milk product is another feature for the user of this website from which he or she can order their expected product. The farms can put their dairy products for selling as well over here. There would be some feature like which farm product, product review, price and availability.
6. Animal doctor would be another feature where it would have some sub feature to ensure the safety of the animals. It would have sub features like level, rating, review, photo, certified, experience, available time, service charge, service providing area etc.
7. Cow food seller is another feature under which there would be some sub feature like level, rating, review, photo, food photo, food price, food expire date, food supply area etc.


**TOOLS & TECHNOLOGY**

**For Website**: HTML, CSS, JS, React, Node Js. 

**For Mobile App**: Dart, Flutter, Firebase.



 **SOCIAL BENEFITS**

1. Making ease of doing business in this area by going digital.


3. We can change the socio-economic aspect of our society by adding the idea of farm sharing which can help in increasing the business.
4. One of our important goal was to change the dynamics of production cycle of milk in our country. We can enhance the production and help our country making it rich. 
 
 **PLANS FOR MONETIZATION**
     
   We will mainly follow two types of monetization strategy,
  
  **Freemium**: 
  The freemium strategy is considered to be the most effective way to monetize this website and app. This website and app will be provided to the users as a freemium version, and it will be completely free to use. We are going to make the money by taking some commission from the farm sharing user from both sides. There will be advertisement as well. 
  
 **Premium**: 
 
  Through premium strategy the user can get the reach of most of the people. It will be like linked in strategy. If you subscribe the premium one then you can reach to the most of the people and there would be no advertisement then.   
  
  # **Software Requirements Specification**

For

# **Milk Basket**

**Prepared by:**

Riaz Rahman Rafi (ID: 1620590642)

Md.Shirajul Islam Shadhin (ID: 1620701042)

shahed ahmed (ID: 1731733042)

March 30th, 2021


# 1.Introduction

**Purpose**

The purpose of Software Requirements Specification (SRS) is to specify the description and specification for our web application and mobile application"Milk Basket". This document will clearly point out what we want to do with our project, how the client will interact with the system, and how the admin will interact with it, also other developers will have a clear idea about our project when they go through this SRS and we can modify it later on.

**Document Conventions**

**Main Title:** Font: Times, Face: Bold, Size 18

**Sub Section Title:** Font: Times, Face: Bold, Size 14

**Other Explanations:** Font: Calibri, Face: Normal, Size: 12

**Intended Audience and Reading Suggestions**

The intended audiences are Clients, Developers, and Project Manager who will evaluate this project. Keeping readability in mind, we have not used any technical terms in this SRS of our project so that everybody can understand it properly. In addition, we have made this system a single vendor system for simplicity's sake. For proper understanding, a reader should start sequentially as mentioned in the table of contents.

  
 **Product Scope**

The purpose of this web and mobile application is to make it easier for people to order food especially, during this pandemic period. Also, our objective is to make the user interface accessible to every age of people so that even an old person can easily get what he or she wants if that person has access to the internet. Most of the current similar type applications do not offer that much flexibility.


**Risk Definition**

The web and mobile application has some restrictions in its usability. A customer cannot add a product to their wish-list, they have to add the product directly to the cart. Customers can only search a product by its name, not by its rating. Finally, if the price of a product changes after a customer buys it, then the system will not generate an alert signal for the customer.


**References**

1. &quot;CSS documentation |CSS documentation | CSS.&quot; https://devdocs.io/css/(accessed Mar. 22, 2021).

2. &quot;REACT documentation |React documentation | REACT.&quot;https://reactjs.org/docs/getting-started.html/(accessed Mar. 22, 2021).

3. &quot;MySQL : MySQL Documentation.&quot; https://dev.mysql.com/doc/ (accessed Mar. 10, 2021).

# **2. Overall description**

**2.1 User Classes and Characteristics**

**User classes--**

The user classes are as follows-

1.**Customer**

The customer will be able to view, rate, ask questions and buy the products. Thus the name, id, product review, items purchased, login information and other details should be present for placement of the orders.

2. **Items**

Each item will have a type, price, title, rating, etc. that will allow the customer to help choose the item.

3. **Shopping cart**

The items that the customers ordered along with their cumulative price including tax are present in the shopping cart.

4. **Payment**

The details of each payment method are needed to ensure a smooth transaction. For example, if the customer chooses to pay via card, then the credit card number, customer details, the bank details will be needed.

5. **Order** 

The order details such as the order number, the details of the customer associated with the order, the product details of the ordered item, etc. are needed for buying the items.

6. **Admin**

The admin can update, maintain the website, and view customer&#39;s details. In order to manage the website properly the admin&#39;s personal information such as id, password, and email will be required.

**User Characteristics**

The user is required to have internet access and have a basic understanding of browsing through websites.

**2.2 User Needs**

Our application is built for customers who want to browse through different items on our websites and purchase them without visiting the shop physically. The customers are able to search for items, add items to the cart and rate the items that they bought. For the ease of customers, there is a FAQ section where the customer can drop questions and also view the previously answered questions regarding some common queries. Likewise, an admin panel is present which can only be accessed by the admins. The admin is able to accept or reject customer requests and also make changes to the website. The admin is also allowed to view customer's personal information but they aren't allowed to change that information.

**2.3 Operating Environment**

The user is required to have a system that supports a web browser as our application is web-based.

**2.4 Constraints**

The constraints are as follows-

- Our application is web-based that is no mobile app is developed for this system.
- The customer needs to the first login in order to buy goods from our online shopping system
- Our system doesn't have a voice search command for the use

**2.5 Assumptions**

It is assumed that the people who will be using our application will have a good knowledge of English, and have an electronic device that will support a web browser like Chrome, Opera, Mozilla Firefox, etc. The user is also required to have an internet connection to access our application.

# **3. Requirements**

**3.1 Functional Requirements**

**User Stories**

1. **Register**

As a customer, I want a register feature so that I can log into the system.

**Confirmation**

- Valid user logged in and redirected to login page
- If registration is failed

- Display &quot;Email format not right&quot;
- Password and confirm password don&#39;t match

- If the user is already registered

- Use another user name

2. **Login**

As a customer, I want a login feature so that I can order items from the site

**Confirmation**

- Valid user logged in, redirect him to homepage

- &quot;Remember me&quot; ticked- ensures automatic login next time
- &quot;Remember me&quot; not ticked- forces user to login next time
- &quot;Forgot password&quot; ticked- save the new password

- Failure

- Display &quot; Incorrect user name try again&quot; if user name is incorrect
- Display &quot; Incorrect password try again&quot;, if password is incorrect
- Display &quot;Did you register yet? Register here&quot;, if user is not registered
- Display &quot;Service unavailable try again later&quot;, if service isn&#39;t available
- Account has expired –refer to renewal page

3. **Product add, update &amp; delete**

As an admin of the site I would want an add, update and delete feature for the product so that I can modify my website.

**Confirmation**

- Add an item to the site
- Update the product if

- It&#39;s model number changes
- It&#39;s price changes
- It runs out of stock, then display &quot;out of stock&quot; message

- Delete the product if validity expires

4. **Searching**

As a customer I want a searching feature, so that I can gather information about the user easily,

**Confirmation**

- If the product is found

- Redirect customer to the product page

- If the product is not found

- Display message not found

- If something similar to the user&#39;s desired product exists-

- Suggest the products

5. **Add to cart**

As a customer I want an add to cart feature so that I can easily order my desired products

**Confirmation**

- Add an item to the cart
- Add an item with its quantity available
- Add an item with its updated price, based on the quantity
- If the desired quantity of the product isn&#39;t available

- Display- &quot;Not available&quot;

- Remove the product if, &quot;Remove button&quot; is pressed
- Calculate the total price including tax

6. **Request Approved:**

As a customer, I want to request for anything I want. As an admin of the site, I want an admin panel to check customer&#39;s request.

**Confirmation**

Admin will have the access to log in.

Admin panel will have a look on customer&#39;s request.

Admin have an understanding of how permissions work.

Admin will decide whether they will grant the request or not.

7. **Payment:**

As a customer, I want a payment feature so that I get to know the bill, pay the bill &amp; know about the payment method.

**Confirmation**

- If the product is added to the cart

- Products bill will add on the payment section.

- If the product is not added to the cart

- Nothing is displayed

- If more products are added to the cart again

- It will add the bill on the cart again.

- Payment Method--

- Customer may pay on online money transfer system

- Customer may pay cash on delivery.

8. **Ratings**

As a user I need to know the ratings of the product so that I can trust the product.

**Confirmation**

- User can rate the product between 0 to 5 stars.
- User can see previous ratings as well.
- User can skip the rating interface if they want.

9. **Frequently Asked Questions (FAQS)**

As a user, I need a FAQ section so that I can get my desired answers regarding this platform.

**Confirmation**

- User can ask questions.
- User can answer questions as well.
- User can see previously asked questions as well.

**3.2 Non-Functional Requirements**

- **Portability:** Systemrunningononeplatformcaneasilybeconvertedtorunonanotherplatform through cross-platform technology.

- **Reliability:** The ability of the system to behave consistently in a user-acceptable manner when operating within the environment for which the system was intended.

- **Availability:** The system should be available at all times, meaning the user can access it using a web browser, only restricted by the down time of the server on which the system runs.

- **Maintainability:** A database is used for maintaining the database and the application server takes care of the site.

- **Security:** Secure access to confidential data (customer information).

- ** User-friendly:** System should be easily used by the customer.

- **Performance:** Performance should be fast.

- **Efficient:** System should be efficient that it won&#39;t get hang if heavy traffic or an order is placed.

- **Safety:** Data in the database of the system should not be lost or damaged.

- **Privacy:** Personal data of this system should not disclose to anyone.

#  **Appendices**

**Glossary:**

| **Term** | **Definition** |
| --- | --- |
| Admin | System administration who is given specific permission for managing and controlling the system |
| User | A customer visiting the page |
| Wish | A desirable level of achievement |

## Documentation Tool
 
### JAVASCRIPT- JSDoc

✨Installation: If you have windows and are running VS Code this is the step by step to getting JSDoc to work.

   VS Code will now provide a JSDoc comment template for JavaScript and TypeScript functions when you type /**: 

Follow the steps: 👍  [Auto JSDoc comment Tutorial](https://code.visualstudio.com/updates/v1_10?fbclid=IwAR154f_HctfNeOAHptI18kFoRImho3GWwOwyJkncgm9iwkH3NfQHKAMGk8s#_auto-jsdoc-comments)

## ✔Using JSDoc:
Follow the steps showed in the YouTube Video below to have an idea about how to generate documentation from Java script source codes using “JSDoc” documentation tool : [Generating Documentation Tutorial](https://youtu.be/icwJYT-Ilpw) 👍 

 🖱🖱Different Tags Tutorial of JSDoc : [JSDoc Document](https://jsdoc.app/)

 🖱🖱Tags Tutorial of JSDoc   :  [JSDoc Wikipedia](https://en.wikipedia.org/wiki/JSDoc)

## 💻Source Code-: 

![Source_Code](https://github.com/CSE327-Project-School-Management-System/School-Management-System/blob/main/Diagrams/JsDoc.png)


 
For more features about JSDoc  : [Details](https://jsdoc.app/about-getting-started.html)


## ✨✨HTML Documentation

![HTML Documentation](https://github.com/CSE327-Project-School-Management-System/School-Management-System/blob/main/Diagrams/HTML%20Documentation.png)



## 👌  JAVASCRIPT



Coding standard are style guidelines for programming. They typically cover:

 •	Naming and declaration rules for variables and functions.
 
 •	Programming practices and principles

Coding standard secure quality:

 •	Improves code readability

 •	Make code maintenance easier


## ✨ Naming Conventions

### ✔ Variable Name:
* 1. All names start with a letter. 
* 2. Every letter will be in "lower case" . 
* 3. For multiple word variable the should in “lower_case_with_underscores”.
* 4. One "var" statement must be used per variable assignment lower case. 
* 5. No limit to the length of the variable name.
* 6. Constants (like PI) written in UPPERCASE,

     * *EXAMPLE* 👇

              var bar = false;
              var a;
              var first_name = "Nusrat";
              const PI = 3.141592653589793; 


 ## ✔Spaces Around Operators: 

Always put spaces around operators ( = + - * / ), and after commas.

   * *EXAMPLE* 👇
  
                 var x = y + z;
                 var values = ["Mahi", "Sahi", "Fiat"];

 ## ✔Object Methods: 

Methods name should be in lower case & should be end a simple statement with a semicolon.

  * *EXAMPLE* 👇
    
           var person = {
           first_name: "Mohsin",
           last_name : "Ara",
           id       : 1829854042,
           full_name : function() {
           return this.first_name + " " + this.last_name;
          }
        };


 ### ✔Classes:
For creating a class in JavaScript use " class " keyword. In the class you can declare or call any method. You can send parameters to class methods. Through this class you can create objects. 

For constructor method you have to give exact name of the "constructor". Its main use is to initialized object properties.  It is executed automatically when a new object is created  

   * *EXAMPLE:* 👇

            class ClassName {
                   constructor ()	{...}
                   method_1 () 	{...}
                   method_2 () 	{...}
                   method_3 () 	{...}
            }



 ## ✔Arrays:
* In JavaScript creating an array is the easiest thing. Just declare the type and the name of the array. You don’t need to set the size of the array. Here spaces and line breaks are not important. 

* var array name = [item1, item2, ...];

* For accessing any element, you have to provide the index number and for accessing the full array use array name. 

* pop () and push () methods are very handy and helpful method for the controlling the array.

   * *EXAMPLE:* 👇

                    var fruits = ["Banana", "Orange", "Apple", "Mango"];
                    fruits.pop();  // Removes the last element ("Mango") from fruits

                    var fruits = ["Banana", "Orange", "Apple", "Mango"];
                    fruits.push("Kiwi");  //  Adds a new element ("Kiwi") to fruits


 ## ✔Switch Statement:
For performing different actions based on different condition there we use switch case. The syntax of JS switch case is pretty much similar with other programming language. 

  * *EXAMPLE:* 👇

            switch(expression) {
                 case x:            
                  break;
                case y:
                  break;
                default:
             }

For breaking out from the switch block JavaScript use break keyword, like others language. The default keyword specifies the code to run if there is no case match.


 ## ✔Indentation and Line Breaks:

Indentation and line breaks add readability to complex statements.
Tabs should be used for indentation. Even if the entire file is contained in a closure (i.e., an immediately invoked function), the contents of that function should be indented by one tab.

  * *EXAMPLE:* 👇

             ( function ( $ ) {
                         // Expressions indented
               function doSomething() {
                        // Expressions indented
                }
            } )( jQuery );


 ## ✔Statement Rules:

General rules for simple statements:
•	Always end a simple statement with a semicolon( ; )
   * *EXAMPLE:* 👇
 
             var values = ["Volvo", "Saab", "Fiat"];
                  var person = {
                   firstName: "John",
                   lastName: "Doe",
                   age: 50,
                   eyeColor: "blue"
              };

✨General rules for complex (compound) statements:
•	Put the opening bracket at the end of the first line.
•	Use one space before the opening bracket.
•	Put the closing bracket on a new line, without leading spaces.
•	Do not end a complex statement with a semicolon.

  * *EXAMPLE:* 👇

              function toCelsius(fahrenheit) {
               return (5 / 9) * (fahrenheit - 32);
              }
       💻_*For Loops*_: * *EXAMPLE:* 👇

                  for (i = 0; i < 5; i++) {
                    x += i;
                   }
       💻_*For Conditionals:*_ * *EXAMPLE:* 👇

                 if (time < 20) {
                   greeting = "Good day";
                 } 
                else {
                   greeting = "Good evening";
                }

 ## ✔Event Handlers:

When using event handlers to listen for browser events it’s a common requirement to want to cancel the default browser action. This should be done by calling the event.preventDefault() method. 
   * *EXAMPLE:* 👇

            jQuery('button').click(function (event) {
                event.preventDefault();
              };

It is also possible to return false from the callback() function. Avoid doing this as it also calls the event.stopPropagation() method which prevents the event from bubbling up the DOM tree. This prevents other handlers listening for the same event.
# **USE CASE DIAGRAM**
![CSE499A-Use-Case-Diagram](https://user-images.githubusercontent.com/44206343/112946705-a9177080-9157-11eb-9d7a-39981e4e4728.png)


**Date/Location:** 17/03/2021

**Attendees:** shirajul islam (SI), Shahed Ahmed(SA), 
          Riaz Rahman Rafi (RR)               

**Start Time:** 10.00pm 

**End Time:** 10.40pm

**Decisions**
========= 
* We choose Web and fluttee as our technology
* We choose react as the framework

**Actions**
======= 
* i. Research on coding standards 
* ii. Research on  documentation tool

 |Action|Allocated team member|Deadline |  
|:------|:-------------------:|:--------|                          
| Action-i | SI, RR  |27/03/2021 |
| Action-ii| SA, SI |27/03/2021 |


 

 	     











