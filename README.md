# E-Commerce Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

* [Description](#description)
* [Visuals](#visuals)
* [Installation](#installation)
* [Technologies](#technologies)
* [Licenses](#licenses)
* [Support](#support)
* [Authors](#authors)
* [Contributions](#contributions)

## Description

Welcome to the E-Commerce Backend, where you can dynamically create, edit, update, and delete products, categories, and product tags to your database with ease. With the addition of front-end fetch requests, you can easily manage your online store without concern of invalid entries.

This application restricts entries into the database to prevent faulty information in your system. For example, you cannot enter products without a name, or update the stock of an item to a non-integer. 

## Visuals

The following image is of the website where you will download Node JS, if necessary.

![node j s website](./Assets/images/Download-Node-js.png)
V
This is a backend application, meaning that there are no visuals to share except a walkthrough video to show you what you can expect in your terminal to show that things are linked correctly. 

[Click here for a video explaining installation and testing of the application](https://drive.google.com/file/d/18LL3mpnkWB_sBItLjntgRZ4OAQmvft6M/view?usp=sharing)

## Installation

To enjoy this application, you will need to install Node JS on your local computer. [Click here for links to download Node JS.](https://nodejs.org/en/download/)

Then, clone this repository to your local computer, and open up the folder in your coding software (i.e. Visual Studio Code). Once open, open up your Terminal (on Mac OS) or GitBash (on Windows OS). You will have to direct yourself to the cloned repository, and then run this command in the terminal: 

`npm install`

This will download the node modules MySQL2, Express, Nodemon, Sequelize, and DOTENV that this application needs to run on your local computer. After install, you will run the following command to open a MySQL shell in your terminal: 

`mysql -u root` 

Then you will install the schema.sql file so MySQL can format your database. The semi-colon is necessary.

`SOURCE db/schema.sql;`

You can exit the shell by entering:

`exit`

And then type:

`nodemon`

If the last message in the terminal says "App listening on port 3001!", then you have installed the program correctly. If you ever need to shut down this server application use this command:

`^C`

[Click here for a video explaining installation and testing of the application](https://drive.google.com/file/d/18LL3mpnkWB_sBItLjntgRZ4OAQmvft6M/view?usp=sharing)

## Technologies

* Node JS
* MySql2
* Sequelize
* DOTENV
* Express

## Licenses

This application uses the MIT Software License. [Click here to view full license.](LICENSE)

## Support

Contact us at devonfaria@gmail.com if you need assistance downloading or activating this repository. You can also find me on [GitHub.](https://github.com/devonfaria)

## Authors

Devon Faria

## Contributions

Thanks you to my tutor, Evan Hardek, for helping me understand Sequelize modulization and how to navigate it successfully.