# Go Food Me

* Nick Wagemann
* Jeremiah Dyck
* Gordon Huang
* Cameron Webbe
* Howard Yuan

A Food Donation crowdfunding application aimed at helping those experiencing challenging circumstances gain access to food during trying times.

## Design

* [API design](docs/apis.md)
* [Data model](docs/data-model.md)
* [GHI](docs/ghi.md)
* [Integrations](docs/integrations.md)

## Intended market

The people that we expect to use this are those
that need food and those that wish to aid those in need of food. 

* People who need Food
* People who wish to donate to those in need of food

## Functionality

# MVP Functionality
* Create User Accounts who can make posts telling there situation, explaining why they need and what food they need , can make posts giving updates and thanks to those donating.
* In order to create content would need to make an account
* Add a "payment" method form to allow people to donate towards person post
* Users and Non-Users will be able to look at posts 
* How it works page explaining the purpose of the website and how it works


# Stretch Goals

* Allow Charity Users to be created that would have their own section for posts
* Posts made by users will be sharable to social media platforms. 
* Version 1 will link to Amazon API to create a shopping list and have it delivered to the address they set
* Updated Version will have the shopping list created by a more local location
* People who donate to buying something off persons wishlist will receive some notification that the item has been recieved
* Person who made post will be able to send a personal thank you message to another user who has donated. Will only work for those who have an account as to protect personal information of donater.
* Search Function to find by user or title of post
* Most viewed posts section or most donated post
* Top Donators per Post
* Comment Section on each post page moderated by the post creator 
* Flag Fundraiser button that goes to site admin to be reviewed if you suspect bad actor
* Language Selector to translate the page into selected language.
* Allow Food Banks to make posts for necessary food products needed by their organization
* Featured Post of the day
* Charity fundraiser related news on landing page

# Startup
* Fork the project
* Clone the project
* Run - docker volume create mongo-data
* Run - docker compose build
* Run - docker compose up