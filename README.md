# CVGS
 
# Owner: Almas Khan
# Project: CVGS gaming store
# About: 
This is a gaming web store where users can register and login to view new released games. They can also purchase and download games through this webstore.
There are many features in the webstore:
* Add friends
* Add games to wishlist and share it on social media
* Register for an gaming event to participate
* Rate and post a review for games
* Add preferences 
* save credit cards for payments.
The webstore also has a admin panel for crud operations of games and events. Admin should also evaluate game reviews before posting on website.

# Navigating through repo
This repo also contains unit testing project for the same project, so if you need just the webstore code go to CVGS folder and clone that folder to your local folder.
* Unit testing is done with Selenium and firefox webdriver, so if you need unit testing code go to UnitTestProject folder and clone it to your local folder. You do need CVGS code to make run the unit testing project. 
-----------------------------------------------------------------------------------------------------------------------------------------------
# Making your project live on Azure
* Used Azure to live the project. The project uses SQL database, so on Azure first made a SQL database with SQL authentication and then open SQL management studio on your local and copy the Azure Sql Database instance and same username and password to connect, then import your local database to the azure database instance, the steps will be straight forward. After this your project database will be up on Azure. After that make a web app service in azure and link your github repo in deployment center, that way Azure will take your code from Git and make it live. Azure directly make a pipeline to git code. To check the status you can go in your git repo under actions you will see deployments logs there. If any error encouters you can easily check it in actions. You have to also change connection string from local SQL database to Azure SQL database. Once Deployement is done you can go to your web app service in azure, on top there is a browse tab if you click on it you will your project up and running.
-----------------------------------------------------------------------------------------------------------------------------------------------
# Link for live project: https://cvgs.azurewebsites.net/
----------------------------------------------------------------------------------------------------------------------------------------------
# How to run project
* The project website has two actors, members and admin. From index page of website go to Login tab, provide username="affan" & password="Test12@12". After login you will see a list of games. You can also register with your own details to become a member. From list of games, you can add them in wishlist or add it to cart, you can also clicks on a game to see its details like rating and reviews. 
----------------------------------------------------------------------------------------------------------------------------------------------
# Future enhancement and bug-fixing
* Whenever you make any changes and commit it to main branch, you don't need to redeploy code on Azure as Azure will detect whenever any changes occur on the code it will automatically redeploy it. There is an option on Azure to redeploy code whenever any changes occur in the git repo.
----------------------------------------------------------------------------------------------------------------------------------------------
