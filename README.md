# EQUIP
EQUIP is a rental buisness inventory management system. 
EQUIP is a buisness and client side interface allowing for seamless interaction for all of your
inventory needs.


### Setup

The app is split into the following 3 components

* server - provides the express server to manage the mongo database through the api's and server assets
* client/Business - provides the business login and inventory UI
* client/Client - provides the client site to check out items

The following should be done to install all dependencies:

#### Server

In the server folder execute:

`npm install` 

#### Client 

In the Client/Business folder execute:

`bower install` 

### Guidelines

- There are two sceenshots in the assets folder.
  One is business-side UI:
  ![Alt text](/app/assets/BusinessUI.png?raw=true "Business-Side UI") 
  The other one is client-side UI:
  ![Alt text](/app/assets/ClientUI.png?raw=true "Client-Side UI") 

- In the server folder, run `npm test` could test server api and database.
  Add you own test in the test folder if you want to make some changes to routes or database.

- Reference API_ROUTES.md and DATABASE_SCHEMA.md documentations when you
  want to make some updates on the front-end side.      

