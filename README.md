[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]




<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Kali Ansible</h3>

  <p align="center">
    Kali automatic provisioning for pentesting and CTFs
    <br />
    <a href="https://github.com/itasahobby/kali_ansible"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/itasahobby/kali_ansible">View Demo</a>
    ·
    <a href="https://github.com/itasahobby/kali_ansible/issues">Report Bug</a>
    ·
    <a href="https://github.com/itasahobby/kali_ansible/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Automatic kali linux provisioning using ansible, includes the following:
* Terminal and directory customization
* Generic tools
* Pentesting related tools

### Built With

* [Ansible](https://www.ansible.com/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

1. Clone the repo
   ```sh
   git clone https://github.com/itasahobby/kali_ansible.git
   ```
2. Step into the cloned directory
   ```sh
   cd kali_ansible
   ```
3. Execute the ansible playbook
    ```sh
    ansible-playbook --ask-become-pass kali-main.yml
    ```

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/itasahobby/kali_ansible/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- CONTACT -->
## Contact

[@jusepe_it](https://twitter.com/jusepe_it)

Project Link: [https://github.com/itasahobby/kali_ansible](https://github.com/itasahobby/kali_ansible)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/itasahobby/kali_ansible.svg?style=for-the-badge
[contributors-url]: https://github.com/itasahobby/kali_ansible/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/itasahobby/kali_ansible.svg?style=for-the-badge
[forks-url]: https://github.com/itasahobby/kali_ansible/network/members
[stars-shield]: https://img.shields.io/github/stars/itasahobby/kali_ansible.svg?style=for-the-badge
[stars-url]: https://github.com/itasahobby/kali_ansible/stargazers
[issues-shield]: https://img.shields.io/github/issues/itasahobby/kali_ansible.svg?style=for-the-badge
[issues-url]: https://github.com/itasahobby/kali_ansible/issues
