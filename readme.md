<a name="readme-top"></a>
<div align="center">

  ![Project Banner](readme_assets/readme_banner.png#gh-dark-mode-only)
  ![Project Banner](readme_assets/readme_banner-light.png#gh-light-mode-only)

  <h1>HooBank</h1>
  
  <p>
    HooBank is a modern UI/UX well-designed web application built with React.js & Tailwind CSS inspired by Figma
  </p>

<!-- Badges -->
<p>
  <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/ladunjexa/Modern-UI.UX-Web" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/ladunjexa/Modern-UI.UX-Web" alt="last update" />
  </a>
  <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/network/members">
    <img src="https://img.shields.io/github/forks/ladunjexa/Modern-UI.UX-Web" alt="forks" />
  </a>
  <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/stargazers">
    <img src="https://img.shields.io/github/stars/ladunjexa/Modern-UI.UX-Web" alt="stars" />
  </a>
  <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/issues/">
    <img src="https://img.shields.io/github/issues/ladunjexa/Modern-UI.UX-Web" alt="open issues" />
  </a>
  <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/ladunjexa/Modern-UI.UX-Web.svg" alt="license" />
  </a>
</p>
   
 <h4>
    <a href="https://modern-ui-ux-web.vercel.app/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/Modern-UI.UX-Web">Documentation</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/Modern-UI.UX-Web/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
<details>

<summary>

# :notebook_with_decorative_cover: Table of Contents

</summary>

- [About the Project](#star2-about-the-project)
  * [Folder Structure](#bangbang-folder-structure)
  * [Tech Stack](#space_invader-tech-stack)
- [Getting Started](#toolbox-getting-started)
  * [Installation](#gear-installation)
  * [Run Locally](#running-run-locally)
- [Contributing](#wave-contributing)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

</details>  

<!-- About the Project -->
## :star2: About the Project

<div align="center">
  <img src="https://camo.githubusercontent.com/c4493d95984ace14ebef070617d63d2fa8068b02a1359d1a311b175ce623026b/68747470733a2f2f692e6962622e636f2f424b31486e30782f53637265656e73686f742d323032322d30382d30382d61742d342d30352d34382d504d2e706e67" height="auto" width="90%"/>
</div>

<br />

This repository houses a fully responsive Modern UI/UX webapp consisting of a stunning hero section, high-quality assets and gradients, business stats, reusable components, CTA, testimonials, and much more - built with React.js & Tailwind CSS ⏪

<!-- Folder Structure -->
### :bangbang: Folder Structure

Here is the folder structure of HooBank.
```
Modern-UI.UX-Web/
|- src/
  |-- assets/
  |-- components/
  |-- constants/
|- App.jsx
|- index.css
|- main.jsx
|- styles.js
```

Now, lets dive into the public and src folders.

### public

`index.html` - `package.json` - `vite.config.js` - `tailwind.config.cjs` - `postcss.config.cjs`

The root folder contains the HTML file so you can tweak it, for example, to set the page title. The <script> tag with the compiled code will be added to it automatically during the build process.
also, can be found other configuration files for Tailwind, PostCSS, Vite and etc.
  
### src

#### components

`Billing.jsx` - `Business.jsx` - `Button.jsx` - `CardDeal.jsx` - `Clients.jsx` - `CTA.jsx` - `FeedbackCard.jsx` - `Footer.jsx` - `GetStarted.jsx` - `Hero.jsx` - `Navbar.jsx` - `Stats.jsx` - `Testimonial.jsx` - `index.js`
  
JSX (JavaScript XML / syntax extension to JavaScript) files contain **HooBank** components which split the UI into independent and reusable bits of code which comes with the full power of JavaScript.
The list above describe what the UI should look like, and any JSX produces React "element" where the file names hint at their contents.

#### constants

`index.js` - JS file for declaration of important objects such as navigation links, features, feedback, social media, clients and etc, let the developer developer more efficiency and comfort in controlling the site's content.

#### assets
  
Very high quality assets files for website visualization, most of them in SVG (Scalable Vector Graphics) format used to describe static or dynamic 2D vector graphics.
  
high-quality assets files 

<br />

<!-- TechStack -->
### :space_invader: Tech Stack
  
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Installation -->
### :gear: Installation

#### Step 1:
Download or clone this repo by using the link below:

```bash
 https://github.com/ladunjexa/Modern-UI.UX-Web
```

#### Step 2:

HooBank using NPM (Node Package Manager), therefore, make sure that Node.js is installed by execute the following command in console:

```bash
  node -v
```

#### Step 3:

At the main folder execute the following command in console to get the required dependencies:

```bash
  npm install
```

<!-- Run Locally -->
### :running: Run Locally

#### Step 1:

At the main folder execute the following command in console to run the development server:

```bash
  npm run dev
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/ladunjexa/Modern-UI.UX-Web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ladunjexa/Modern-UI.UX-Web" />
</a>


Contributions are always welcome!

See [`contributing.md`](https://contributing.md/) for ways to get started.

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- License -->
## :warning: License

Distributed under the MIT License. See [LICENSE.txt](https://github.com/ladunjexa/Modern-UI.UX-Web/blob/main/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contact -->
## :handshake: Contact

Liron Abutbul - [@lironabutbul6](https://twitter.com/lironabutbul6) - [@ladunjexa](https://t.me/ladunjexa)

Project Link: [https://github.com/ladunjexa/Modern-UI.UX-Web](https://github.com/ladunjexa/Modern-UI.UX-Web)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Acknowledgments -->
## :gem: Acknowledgements

This section used to mention useful resources and libraries that used in HooBank

 - [HooBank - Figma Design](https://www.figma.com/file/bUGIPys15E78w9bs1l4tgS/HooBank?node-id=310%3A485&t=e0dGnlPUHU1m8cG0-0)
 - #JSMastery

<p align="right">(<a href="#readme-top">back to top</a>)</p>
