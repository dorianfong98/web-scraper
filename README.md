


<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->




<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This is a Web Scraper application built to extract data from any web page quickly and accurately.

Built with Javascript, Node.js, and Express.js, Axios and Cheerio dependencies for npm.

This particular application I have coded specifically extracts headlines and article links from UK news source The Guardian, but you may modify and adapt the code accordingly for any other Website's HTML elements.

[Express.js](https://expressjs.com/) is a Node.js back end web application framework that provides broad features for building web and mobile applications. It is used to build a single page, multipage, and hybrid web application. 

[Cheerio](https://www.npmjs.com/package/cheerio) is a package to pick out HTML elements on a web page. It works by parsing markup and provides an API for traversing and manipulating the resulting data structure. Cheerio's selector implementation is nearly identical to that of jQuery.

[Axios](https://www.npmjs.com/package/axios), a rather popular and widely-used package, is a promise-based HTTP client for the browser and Node.js. Axios essentially makes it easy to send HTTP requests to rest endpoints and perform CRUD operations - this means that it can be used to get, post, put and delete data. 
 
## Getting Started

To get started using the application, simply download the .zip file and open the web-scraper.exe executable. 

Note: As this file runs on PORT 3000, make sure that it is not already in use. 
To check and kill processes running on the port:

For **Linux/Mac OS** search (sudo) run this in the terminal:

`$ lsof -i tcp:3000` <br />
`$ kill -9 PID`

On **Windows**:

`netstat -ano | findstr :3000`<br />
`tskill typeyourPIDhere` 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

This particular application I have coded specifically extracts headlines and article links from UK news source The Guardian, but you may modify and adapt the code accordingly for **any other Website's HTML elements.**

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Dorian Fong - [My Website](https://dorianfong98.github.io/) | [My Email](mailto:dorianfong@u.nus.edu) | [My LinkedIn](https://www.linkedin.com/in/dorianfong/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

