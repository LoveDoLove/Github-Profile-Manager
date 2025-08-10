<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]

<br />
<div align="center">
  <a href="https://github.com/LoveDoLove/Github-Profile-Manager">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">GitHub Profile Manager</h3>

  <p align="center">
    Automate your GitHub profile README with dynamic featured projects and 3D contribution graphs using GitHub Actions workflows.
    <br />
    <a href="https://github.com/LoveDoLove/Github-Profile-Manager"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/LoveDoLove/Github-Profile-Manager">View Demo</a>
    &middot;
    <a href="https://github.com/LoveDoLove/Github-Profile-Manager/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/LoveDoLove/Github-Profile-Manager/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<details>
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
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

**GitHub Profile Manager** automates your GitHub profile README by dynamically updating featured repositories based on stars and displaying a 3D contribution graph. All updates are handled via GitHub Actions workflows—no manual script running required.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
- [![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
- [![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://daringfireball.net/projects/markdown/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

### Prerequisites

- A GitHub repository with a profile README (e.g., `<username>/<username>`)
- GitHub Actions enabled

### Installation

1. Copy the workflow YAML files from the `workflows/` directory into your repository's `.github/workflows` directory:
   - [`generate-3d-contribution-graph.yml`](workflows/generate-3d-contribution-graph.yml)
   - [`sync-top-starred-projects.yml`](workflows/sync-top-starred-projects.yml)
2. (Optional) Add a repository environment variable named `EXCLUDE_REPOS` in your GitHub repository settings to exclude specific repositories from the featured list. Use a comma-separated list (e.g., `repo1,repo2`).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

- **Automatic Featured Projects:**  
  The `sync-top-starred-projects.yml` workflow will automatically update your profile README with your top-starred repositories on a schedule or on demand.
- **Exclude Repositories:**  
  To skip certain repositories, set the `EXCLUDE_REPOS` repository environment variable in your GitHub settings.
- **3D Contribution Graph:**  
  The `generate-3d-contribution-graph.yml` workflow generates a 3D contribution graph SVG, which you can embed in your profile README.
- **No Manual Script Running:**  
  All updates are handled by GitHub Actions; you do not need to run scripts locally.

_For more examples, refer to the [Documentation](https://github.com/LoveDoLove/Github-Profile-Manager)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".  
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/LoveDoLove/Github-Profile-Manager/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LoveDoLove/Github-Profile-Manager" alt="contrib.rocks image" />
</a>

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

LoveDoLove - [@LoveDoLove](https://twitter.com/LoveDoLove) - lovedolove@gmail.com

Project Link: [https://github.com/LoveDoLove/Github-Profile-Manager](https://github.com/LoveDoLove/Github-Profile-Manager)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
- [contrib.rocks](https://contrib.rocks/)
- [GitHub Actions](https://github.com/features/actions)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/LoveDoLove/Github-Profile-Manager.svg?style=for-the-badge
[contributors-url]: https://github.com/LoveDoLove/Github-Profile-Manager/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/LoveDoLove/Github-Profile-Manager.svg?style=for-the-badge
[forks-url]: https://github.com/LoveDoLove/Github-Profile-Manager/network/members
[stars-shield]: https://img.shields.io/github/stars/LoveDoLove/Github-Profile-Manager.svg?style=for-the-badge
[stars-url]: https://github.com/LoveDoLove/Github-Profile-Manager/stargazers
[issues-shield]: https://img.shields.io/github/issues/LoveDoLove/Github-Profile-Manager.svg?style=for-the-badge
[issues-url]: https://github.com/LoveDoLove/Github-Profile-Manager/issues
[license-shield]: https://img.shields.io/github/license/LoveDoLove/Github-Profile-Manager.svg?style=for-the-badge
[license-url]: https://github.com/LoveDoLove/Github-Profile-Manager/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/lovedolove
[product-screenshot]: images/screenshot.png
