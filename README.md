<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/IsaiahSimon">
    <img src="https://github.com/IsaiahSimon/IsaiahSimon/blob/main/images/logo_500x500_dark.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Austere Blog</h3>

  <p align="center">
    A minimalistic personal blog generated using EJS layout and templating!
    <br />
    <a href="https://github.com/IsaiahSimon/austere-blog"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://austere-blog.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/IsaiahSimon/austere-blog/issues">Report Bug</a>
    ·
    <a href="https://github.com/IsaiahSimon/austere-blog/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#lessons-learned">Lessons Learned</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://austere-blog.herokuapp.com/)

A beautiful minimalistic personal blog website. Features a header with navbar and brand, a sticky footer and multiple pages, all generated using EJS partials.

* You can read individual posts on their own generate page.
* You can dynamically compose new posts using the hidden "/compose" page.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [Node.js](https://nodejs.dev/)
* [Express.js](https://expressjs.com/)
* [EJS](https://ejs.co/)
* [Mongoose](https://mongoosejs.com/)
* [MongoDB Atlas](https://www.mongodb.com/atlas)
* [Heroku](https://www.heroku.com/)
* [Lodash](https://lodash.com/)
* [JavaScript](https://www.javascript.com/)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LESSONS LEARNED -->
## Lessons Learned
<details>
<summary>
Ironically, I learned a great deal about serverless deployment using Netlify and AWS Lambda, even though this project is now deployed on Heroku...
</summary>

Ultimately I couldn't get the EJS that this project relies on to play nicely with Netlify Functions. I believe this to be an access issue since private server-side Functions are handled by AWS Lambda, and public static resources are distributed across Netlify's CDN.

I will be revisiting this deployment strategy in another project, or update this one when I have more insight.

**Netlify serverless:**
- using Netlify CLI to deploy an app to production
- built a netlify-express demo app to learn the process
- preparing an app for serverless deployment
- netilify.toml, build command and redirects
- how functions within the "my_functions" folder are handled by AWS Lambda
- how static resources are distributed from the publish directory, "dist" folder, across Netlify's CDN
- how configure environment vars on Netlify
</details>

<!-- GETTING STARTED -->
## Getting Started
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/IsaiahSimon/austere-blog.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Set up the project locally or use the [demo](https://austere-blog.herokuapp.com/) of the fullstack app.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Improve front-end UI
- [ ] Add login page for composing new posts


See the [open issues](https://github.com/IsaiahSimon/austere-blog/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@iSimonDev](https://twitter.com/iSimonDev) - isimon.dev@gmail.com

Project Link: [https://github.com/IsaiahSimon/austere-blog](https://github.com/IsaiahSimon/austere-blog)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Working with multiple Git remotes](https://jigarius.com/blog/multiple-git-remote-repositories)
* [Preparing a Codebase for Heroku Deployment](https://devcenter.heroku.com/articles/preparing-a-codebase-for-heroku-deployment)
* [Heroku Express App Vs Netlify Serverless App](https://www.youtube.com/watch?v=hpvCd5WKGLU)
* [A better git log](https://coderwall.com/p/euwpig/a-better-git-log)
* [Define config vars](https://devcenter.heroku.com/articles/getting-started-with-nodejs#define-config-vars)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/IsaiahSimon/austere-blog.svg?style=for-the-badge
[contributors-url]: https://github.com/IsaiahSimon/austere-blog/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/IsaiahSimon/austere-blog.svg?style=for-the-badge
[forks-url]: https://github.com/IsaiahSimon/austere-blog/network/members
[stars-shield]: https://img.shields.io/github/stars/IsaiahSimon/austere-blog.svg?style=for-the-badge
[stars-url]: https://github.com/IsaiahSimon/austere-blog/stargazers
[issues-shield]: https://img.shields.io/github/issues/IsaiahSimon/austere-blog.svg?style=for-the-badge
[issues-url]: https://github.com/IsaiahSimon/austere-blog/issues
[license-shield]: https://img.shields.io/github/license/IsaiahSimon/austere-blog.svg?style=for-the-badge
[license-url]: https://github.com/IsaiahSimon/austere-blog/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/isaiahsimon101
[product-screenshot]: ./public/images/gif-austere.gif