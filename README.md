# Emaily
This project was built as part of Stephen Grider's Udemy course, "Node with React: Fullstack Web Development".

Emaily is a web application that allows companies to obtain feedback on their products, in a very efficient way. Emaily lets the user create a survey about their product, typically about a particularly feature of their product, or sometimes even just the product in general. After this survey is created, it is then sent via email to the list of people they want to obtain feedback from. As people respond to these emails, the responses are continuously sent back to the Emaily website for the user/company to see.

Emaily was built using React, Redux, Express and MongoDB.

## Full list of Emaily's features
- Allows users to create profiles for themselves (using Google OAuth authentication)
- Handles credit card payments that needed in order to send out the surveys (using Stripe)
- Allows automated emails containing the user's specific survery to be sent out to various people (using SendGrid)
- Stores all of the user's previously sent surveys (and responses to the surveys) in a database for the user's future use (using MongoDB)

## A link to the Emaily web application
Although the name of this application is Emaily, the website's name is "pure journey 49453", because this is the default name that Heroku gave it when it was deployed.

https://pure-journey-49453.herokuapp.com
