# ECommerceBackEnd

## Description
The E-Commerce back-end app allows a user to build their e-commerce database and inventory. You can add in categories, products, and tags. Associate each product to a category and give each product description tags for easier sorting. 

## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Testing](#testing)
  - [Contributions](#contributions)  
  - [Questions and Contact](#questions-and-contact)
  - [Credits](#credits)

## Installation
- To install this application, first clone to repo to your local device.
- Make sure to install node.
- Run ***npm init***
- Run ***npm install***
- Create the DB in mySQL.
- Run ***node seeds/index.js*** to seed the DB with pre-set data.
- Run ***node server.js*** to start the server.

Make sure that you enter your mysql username and password in the .env file to link to your mysql database.

## Usage
This app uses postman to view, add, change, or delete a category, product, or tag within the database.
The following is the instructions for the PRODUCT route. Follow these same instructions for the CATEGORY and TAG routes:

- To return a full list: Use GET and the /api/products endpoint. Endpoints are listed in the routes files for reference.
- Return just one item: use GET and the /api/products/:id endpoint.
- Create a new item: POST and the /api/products endpoint. In the body, create the appropriate key/value pairs. When creating tag ids, use the following format --> Key: tagIds[index] & value: number. Create a new line item for the next index in the array for each tag id that is to be included.
- Update an item: Use PUT and the /api/products/:id endpoint. Adjust any of the values in the body keys that need to be changed for that id.
- Delete an item: use DELETE and the /api/products/:id endpoint. 

To stop at any point, type in ***ctrl c*** in the terminal and hit enter.

![Gif of running Application](ecommercevideo.gif)

## License
 ![badge](https://img.shields.io/badge/license-mit-blue?style=flat-square)<br>
  This application is licensed under the MIT license. Please click the link to read more about the license!<br>
  [License Information](https://choosealicense.com/licenses/mit/)

## Testing
Not available for this application.

## Contributions
:busts_in_silhouette:<br>
If you wish to contribute, please feel free to open an issue so we can discuss your ideas and develop a plan to move forward!
Pull requests will not be accepted without prior discussion, thank you. 

## Questions and Contact
  :grey_question::grey_question:<br>
  Please visit my GitHub profile <br>
  :octocat: https://github.com/aanolan51 <br><br>
  Feel free to drop me a line! <br> :fountain_pen: nolana464@gmail.com

## Credits:
1. https://sequelize.org/master/manual/validations-and-constraints.html
2. https://bezkoder.com/sequelize-associate-many-to-many/