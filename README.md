![License](https://img.shields.io/badge/License-MIT-green.svg)

# object-relational-mapping 
## Ecommerce Backend 
AS A manager at an internet retail company I WANT a back end for my e-commerce website that uses the latest technologies SO THAT my company can compete with other e-commerce companies

## Table of Contents
  
  - [Installation](#installation)
  - [Usage](#usage)
  - [GIF](#gif)
  - [Testing](#testing)
  - [Support](#support)
  - [Contributing](#contributing)
  - [License](#license)
  - [Questions](#questions)
  
  ## Installation

  The key tools to making this project work are npm node modules. The user must run "npm i" to install all the dependencies required to make the backened work like sequalize, express, mysql, nodemon, dotenv. This will allow the user to access the key packages of node that make this function. Once they user does that a personal .env folder must be made containing the set up:
    DB_USER=''
    DB_PW=''
    DB_NAME='ecommerce_db'  
  This will allow the user to access the required database mysql is generating to run this progam. Then they must create the data base either by the command line accessing mysql or in the mysql work bench. Once logged into mysql copy the schema.
  Then the user must seed the database to see how this particular program works. Run the command "npm run seed" this will pull over all the data already set up to see how this program runs. "npm start" will begin the program. A user can use a progam like Insomnia to access the back end since there is no front end for the ecommerce website. 
  
  ## Usage
  
  This code was designed particularly for the data provided but can be a good starting framework for any backend ecommerce style webpage. This framework is able to take products, prices, and inventory and update, add and delete items while categorizing them by tags which means it could be easily searchable with a front end. 

  ## Gif 

  ![gif]()
  
  ## Testing

  Testing is as easy as it sounds. Fork this program, make sure you install the npm packages to your local computer and use a program that can serve API routes like Insomnia. This makes it simple and easy to test the routes and display all key information. 
  
  ## Support
  
  Please [open an issue](https://github.com/mschall217/object-relational-mapping /issues/new) for support.
  
  ## Contributing
  
  My tutors/TAs/Classmates! Thanks as always!
  
  ## License

  MIT License

    Copyright (c) 2021 Morgan Schall
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
  
  ## Questions 
  If you have any questions or concerns please reach out to Morgan Schall on GitHub at mschall217 or email at morgan.allison.schall@gmail.com 
  