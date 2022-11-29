<!-- CODE TO FIX CHALLENGE -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT'S TITLE -->
<a name="readme-top"></a>
<h1 align="center">
  <a href="#"> CODE TO FIX CHALLENGE </a>
</h1>


<!-- PROJECT'S STATUS -->
<h4 align="center"> 
  Status: Finished
</h4>


<!-- TABLE OF CONTENTS DETAIL -->
<p align="center">
  <a href="#about-the-project">About</a> •
  <a href="#features">💻 Features</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#requirements">Requirements</a> •
  <a href="#starting">Starting</a> •
  <a href="#license">:memo: License</a> •
  <a href="#contact">:mailbox_with_mail: Contact</a> •
  <a href="#acknowledgments">Acknowledgments</a>  
</p>


<!-- TABLE OF CONTENTS DETAIL -->
<details>
  <summary>Table of Contents Detail</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">:rocket: Built With</a></li>
      </ul>
    </li>
    <li><a href="#features">💻 Features</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#requirements">Requirements</a></li>
    <li>
      <a href="#starting">Getting Started</a>
      <ul>
        <li><a href="#install">🛠️ Installation Steps</a></li>
        <li><a href="#running">:zap: Running...</a></li>
      </ul>
    </li>
    <li><a href="#license">:memo: License</a></li>
    <li><a href="#contact">:mailbox_with_mail: Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



## About The Project

In this challenge, we have a `Node.js` application that is in the development process, but already has the necessary `tests` to do all the requirements validation. After some changes in the application code, part of the tests stopped passing and now only you can solve this problem. Let's do it?

<a name="built-with"></a>
### :rocket: Built With
This project was developed with the following technology:

[![Javascript][js-shield]][js-url]
[![Node-JS][node-shield]][node-url]
[![Express-JS][express-shield]][express-url]
[![Jest-JS][jest-shield]][jest-url]
<!-- [![Editor-Config][editor-config-shield]][editor-config-url] -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<a name="features"></a>
## 💻 Features

The structure of a repository when it is created is as follows: 
```javascript
{
  id: uuid(),
  title,
  url,
  techs,
  likes: 0
}
```
Description of each property:

- **id** must be a valid `uuid`;
- **title** is the title of the repository;
- **url** is the URL that points to the repository;
- **techs** is an array where each element must be a string with the name of a technology related to the repository;
- **likes** is the number of likes the repository has received (and will be incremented by 1 on 1 with each call in the likes route).

Note that the amount of likes must always be zero at creation time.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Prerequisites

For this project you should to have basic konwledgement about: 
- Javascript, Node.JS, Express.JS and Yarn;
- Http verbs, request and response;
- Basic knowledgement about request's parameters;
- Basic knowledgement about Jest (tests);

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Requirements

For this project you will need:
- NodeJS LTS (18.12.0+);
- Yarn LTS (1.22.19+).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<a name="starting"></a>
## Getting Start

To get a local copy, setting up and running the project, follow these simple steps.

<a name="install"></a>
### 🛠️ Installation Steps
1. Clone the repository
```Bash
git clone https://github.com/sidneyaquino/rocketseat-ignite-node-05-code-to-fix-challenge-js
```
2. Go into the project folder

3. Install dependencies (packages):
```bash
yarn install
```

<a name="running"></a>
### :zap: Runnig...
In the projet folder execute the commands:
```bash
yarn dev   # nodemon.
```
or
```bash
yarn test  # jest.
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<a name="license"></a>
## :memo: License
This project is under the MIT license. See the file [LICENSE](LICENSE.md) for more details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<a name="contact"></a>
## :mailbox_with_mail: Contact
Made by *Sidney Aquino*, **get in Touch!** 
[![LinkedIn][linkedin-shield]][linkedin-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Acknowledgments
>[Rocketseat Ignite - Node.JS Bootcamp](https://app.rocketseat.com.br/ignite/node-js?&) 

Build scalable and simple architectures for the web with `Node.JS` using `Javascript`, a flexible and popular language. Through a hands-on methodology based on the pillars of focus, practice, and group, you will prepare for real-world challenges and develop the behavioral skills to excel in the marketplace.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[js-shield]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[js-url]: https://en.wikipedia.org/wiki/ECMAScript#13th_Edition_%E2%80%93_ECMAScript_2022
[node-shield]: https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
[node-url]: https://nodejs.org
[express-shield]: https://img.shields.io/badge/Express.js-404D59?style=for-the-badge
[express-url]: http://expressjs.com/
[jest-shield]: https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=Jest&logoColor=white
[jest-url]: https://jestjs.io/
[editor-config-shield]: https://img.shields.io/badge/Editor%20Config-E0EFEF?style=for-the-badge&logo=editorconfig&logoColor=000
[editor-config-url]: https://editorconfig.org/
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://de.linkedin.com/in/sidneydeaquino