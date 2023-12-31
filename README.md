<div align="center">


  <img src="https://github.com/sanskargouchandra/pricechecker/assets/117097248/7fdd22d1-ee0c-4370-b860-de37933f1546" width='400' alt="logo" />
  
  # Price-Checker with NEXT.JS!
  
  <p>
A full-fleshed webscraper web app build on Next.js13 with tracking the prices of different product you want, and send email when the price become lowest with help of cron and nodemailer. In this project we use brightdata for scraping data from Web.
  </p>
  
  
<!-- Badges -->

<a href="https://pricechecker-one.vercel.app/" target="_blank">![](https://img.shields.io/website-up-down-green-red/http/monip.org.svg)</a>
![](https://img.shields.io/badge/Maintained-Yes-indigo)
![](https://img.shields.io/github/forks/SashenJayathilaka/AMAZON-Clone.svg)
![](https://img.shields.io/github/stars/SashenJayathilaka/AMAZON-Clone.svg)
![](https://img.shields.io/github/issues/SashenJayathilaka/AMAZON-Clone)
![](https://img.shields.io/github/last-commit/SashenJayathilaka/AMAZON-Clone)

<h4>
    <a href="https://pricechecker-one.vercel.app"/>View Demo</a>
  <span> · </span>
    <a href="https://github.com/sanskargouchandra/pricechecker/blob/master/README.md">Documentation</a>
  <span> · </span>
    <a href="https://github.com/sanskargouchandra/pricechecker/issues">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/sanskargouchandra/pricechecker/issues">Request Feature</a>
  </h4>
</div>

<br />



## :star2: Overview

Welcome to the PriceChecker project, a comprehensive solution for tracking product prices on Amazon. This project is designed to scrape product details from Amazon, store the data in a MongoDB database, and send email notifications to users when there are changes in the product details. The project includes a web application with a user-friendly interface that allows users to search for products, view product details, and subscribe to product updates. The application is built with Next.js and Tailwind CSS, and it includes several components such as a home page, product details page, navbar, search bar, product card, price info card, and modal.

The server-side logic is implemented with serverless functions that handle various tasks such as connecting to the database, scraping product details, updating product information, and sending email notifications. The project also includes several utility functions for extracting information from web pages and formatting numbers.

# :space_invader: Technologies and Frameworks

- Next.js: A React framework for building web applications. It is used for both the frontend and the backend of the application.
- Tailwind CSS: A utility-first CSS framework for rapidly building custom designs. It is used for styling the application.
- TypeScript: A statically typed superset of JavaScript. It is used for writing the code.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js. It is used for defining the product schema and interacting with the MongoDB database.
- Nodemailer: A module for Node.js applications to allow easy email sending. It is used for sending email notifications to users.
- Axios: A promise-based HTTP client for the browser and Node.js. It is used for making HTTP requests to scrape product details from Amazon.
- Cheerio: A fast, flexible, and lean implementation of core jQuery designed specifically for the server. It is used for parsing the HTML response from the Amazon product page.
- React Responsive Carousel: A lightweight carousel component for React. It is used for displaying a carousel of images on the home page.
- Google Fonts: A library of free licensed font families. It is used for defining the font styles in the application.

- 
# :gear: Installation


## :toolbox: Getting Started

### :bangbang: Prerequisites

- Create BrightData account <a href='https://brightdata.com/'>HERE</a>
Than got to Amazon-Webscraper and Copy API key and paste it on .env file.
for Refrence `.env.example` file is on Repo.
</br>
Follow these steps to install and run the project:

1. **Clone the repository**

   Open your terminal and run the following command to clone the repository:

   ```bash
   git clone https://github.com/adrianhajdin/pricewise.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd pricewise
   ```

3. **Install Node.js**

   The project requires Node.js to run. If you don't have it installed, you can download it from [here](https://nodejs.org/en/download/).

4. **Install the required packages**

   The project requires several packages to be installed. Run the following command to install them:

   ```bash
   npm i
   ```

5. **Install the required fonts**

   The project requires the "font-inter" and "font-spaceGrotesk" fonts to be available. You can download them from [Google Fonts](https://fonts.google.com/).

6. **Set up the environment variables**

   The project requires the MONGODB_URI environment variable to be defined. You can do this in a `.env` file in the root of your project:

   ```bash
   MONGODB_URI=your_mongodb_uri
   ```

7. **Start the server**

   Run the following command to start the server:

   ```bash
   npm run start
   ```

Now, you should be able to access the project at `http://localhost:3000`.


<br />

<div align="center">Don't forget to leave a star ⭐️</div>
