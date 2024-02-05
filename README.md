<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url] -->
<div align="center">

[![Status][status-shield]][project-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

[![Build][build-shield]]()
[![Docker-Release][docker-release-shield]][release-url]
[![release-date][release-date-shield]][release-url]


</div>
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/MRSessions/simple-pocket-crm">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <!-- <h1 align="center"><s>PocketBase Vue Starter</s></h1> -->
  <h1 align="center">Simple Pocket CRM</h1>

  <p align="center">
    A simple lightweight CRM built with Pocketbase and Vue
    <!-- <br /> -->
    <!-- <a href="https://github.com/MRSessions/simple-pocket-crm"><strong>Explore the docs »</strong></a> -->
    <br />
    <br />
    <!-- <a href="https://github.com/MRSessions/simple-pocket-crm">View Demo</a>
    · -->
    <a href="https://github.com/MRSessions/simple-pocket-crm/issues">Report Bug</a>
    ·
    <a href="https://github.com/MRSessions/simple-pocket-crm/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<!-- <details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li>
          <a href="#installation-and-setup">Installation and Setup</a>
            <ul><a href="#docker-dev-environments">Docker Dev Environments</a></ul>
            <ul><a href="#local-non-docker">Local (Non-Docker)</a></ul>
            <ul><a href="#docker">Docker</a></ul>
        </li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details> -->



<!-- ABOUT THE PROJECT -->
<!-- ## About The Project -->

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

<!-- Thanks to all the people who have contributed to expanding this template! -->

<!-- <p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- ### Built With

* [![Docker][docker-shield]][docker-url]
* [![PocketBase][PocketBase.io]][Pocketbase-url]
* [![Vue][Vue.js]][Vue-url]
* [![Vuetify][Vuetify.js]][Vuetify-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- GETTING STARTED -->
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Node 20.11.0+](https://nodejs.org/en/download/)
- [Go 1.21.6+](https://go.dev/dl/)
- [Docker (Recommended)](https://docker.com/get-started)

### Installation and Setup

1. Clone the repo
   ```sh
   git clone https://github.com/MRSessions/simple-pocket-crm.git
    ```

#### Local (Non-Docker)

> *Note: You can run the project separately with the default ports 8090 (PocketBase) and 3000 (Vue). The defult .env file is using `VITE_POCKETBASE_URL` to set the PocketBase URL. You can change this to point to a different PocketBase instance or if you change the port.*

1. In the pocketbase directory, run the following command to start the PocketBase server
    ```sh
    go run . serve #Runs PocketBase on default port 8090
    ```
2. In the vue-client directory, install NPM packages
    ```sh
    npm install
    ```
3. In the vue-client directory, run the following command to start the Vue server
    ```sh
    npm run dev #Runs Vue on default port 3000
    ```

#### Docker

- The easiest way to run is use Docker Compose
    ```sh
    docker-compose up --build
    ```
    or to recreate the container
    ```sh
    docker-compose up --build --force-recreate
    ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
<!-- ## Usage

### PocketBase

#### Defaults

### Vue -->

<!-- <p align="right">(<a href="#readme-top">back to top</a>)</p> -->

<!-- ROADMAP -->
<!-- ## Roadmap -->

<!-- - [x] Add section on migrations.
- [x] Add default layout
- [x] Create initialize PB page in Vue to create first PocketBase Admin
- [x] Clean up README.md
  - [x] [Add Pocketbase Typegen](https://github.com/patmood/pocketbase-typegen) (Generate typescript definitions from your pocketbase.io schema.) documentation
- [ ] Create a Docker Dev Environment
- [ ] Add a section for a quick how to use the PocketBase API in Vue (Refer to the [PocketBase API Docs](https://pocketbase.io/docs/api)) -->

<!-- See the [open issues](https://github.com/MRSessions/simple-pocket-crm/issues) for a full list of proposed features (and known issues). -->

<!-- <p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature (`git checkout -b feature/AmazingFeature`) or Bug Fix (`git checkout -b bug/AmazingBugFix`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature or some AmazingBugFix'`)
4. Push to the Branch (`git push origin feature/AmazingFeature` or `git push origin bug/AmazingBugFix`)
5. Open a Pull Request
   1. If your change includes quite a bit of change, please document the changes in detail in the pull request.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Matt Sessions - [@MRSessions](https://github.com/MRSessions)

Project Link: [https://github.com/MRSessions/simple-pocket-crm](https://github.com/MRSessions/simple-pocket-crm)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
<!-- ## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[project-url]: https://github.com/MRSessions/simple-pocket-crm
[status-shield]: https://img.shields.io/badge/status-active-success.svg?style=for-the-badge
[forks-shield]: https://img.shields.io/github/forks/MRSessions/simple-pocket-crm.svg?style=for-the-badge
[forks-url]: https://github.com/MRSessions/simple-pocket-crm/network/members
[stars-shield]: https://img.shields.io/github/stars/MRSessions/simple-pocket-crm.svg?style=for-the-badge
[stars-url]: https://github.com/MRSessions/simple-pocket-crm/stargazers
[issues-shield]: https://img.shields.io/github/issues/MRSessions/simple-pocket-crm.svg?style=for-the-badge
[issues-url]: https://github.com/MRSessions/simple-pocket-crm/issues
[license-shield]: https://img.shields.io/github/license/MRSessions/simple-pocket-crm.svg?style=for-the-badge
[license-url]: https://github.com/MRSessions/simple-pocket-crm/blob/master/LICENSE
[build-shield]: https://img.shields.io/github/actions/workflow/status/MRsessions/simple-pocket-crm/build-single-docker-image.yml?style=for-the-badge
[build-url]: https://github.com/MRSessions/simple-pocket-crm/actions
[prerelease-shield]: https://img.shields.io/github/v/release/MRSessions/simple-pocket-crm?color=s&include_prereleases&label=Pre-release&logo=s&logoColor=s&style=for-the-badge
[release-date-shield]: https://img.shields.io/github/release-date-pre/mrsessions/simple-pocket-crm?label=Released&style=for-the-badge
[docker-release-shield]: https://img.shields.io/github/v/tag/mrsessions/simple-pocket-crm?include_prereleases&label=docker&style=for-the-badge
[release-url]: https://github.com/MRSessions/simple-pocket-crm/pkgs/container/simple-pocket-crm


[Vue.js]: https://img.shields.io/badge/Vue.js-3.2.38+-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Vuetify.js]: https://img.shields.io/badge/Vuetify-3.0.0+-green?style=for-the-badge&logo=vuetify&logoColor=blue
[Vuetify-url]: https://next.vuetifyjs.com/en/
[PocketBase.io]: https://img.shields.io/badge/PocketBase-0.13.2+-b8dbe4?style=for-the-badge&logo=pocketbase&logoColor=b8dbe4
[Pocketbase-url]: https://pocketbase.io
[docker-shield]: https://img.shields.io/badge/Docker-latest-blue?style=for-the-badge&logo=docker&logoColor=blue
[docker-url]: https://docker.com


<!-- Created with the help of https://github.com/othneildrew/Best-README-Template/pull/73 -->
