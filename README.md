<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dylansnow/vimba_pose_detection">
    <img src="images/example_frame_capture" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Vimba Pose Detection</h3>

  <p align="center">
    This project aims to link MediaPipe's pose detection capabilities with the super high framerates of Allied Vision USB cameras to generate realistic motion capture
    <br />
    <a href="https://github.com/dylansnow/vimba_pose_detection"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/dylansnow/vimba_pose_detection">View Demo</a>
    ·
    <a href="https://github.com/dylansnow/vimba_pose_detection/issues">Report Bug</a>
    ·
    <a href="https://github.com/dylansnow/vimba_pose_detection/issues">Request Feature</a>
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
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
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

This project aims to link MediaPipe's pose detection capabilities with the super high framerates of Allied Vision USB cameras to generate realistic motion capture

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python](https://www.python.org/)
* [Vimba (included at *Vimba_5.0* folder)](https://www.alliedvision.com/en/products/vimba-sdk/)
* [MediaPipe](https://google.github.io/mediapipe/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Install/ configure the following:
* Python (version 3.7 or greater), which includes Pip
  [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
  ```sh
  python --version 
  python -m pip --version
  python -m venv venv
  ./venv/Scripts/activate # Windows only
  source venv/bin/activate # Linux only
  ```
* Vimba SDK
  [https://www.alliedvision.com/en/products/vimba-sdk/](https://www.alliedvision.com/en/products/vimba-sdk/)
* Relevant Pip packages, using the SDK scripts (which are copied and pasted from the installation folder into */Vimba_5.0*)
  ```sh
  cd Vimba_5.0/VimbaPython/Source
  python -m pip install .[numpy-export,opencv-export]
  ```
* Run the scripts!
  ```sh
  python vimba_view_camera.py
  ```


### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/dylansnow/vimba_pose_detection.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [X] Feature 1
- [] Feature 2
- [] Feature 3
    - [] Nested Feature

See the [open issues](https://github.com/dylansnow/vimba_pose_detection/issues) for a full list of proposed features (and known issues).

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

Project Link: [https://github.com/dylansnow/vimba_pose_detection](https://github.com/dylansnow/vimba_pose_detection)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/dylansnow/vimba_pose_detection.svg?style=for-the-badge
[contributors-url]: https://github.com/dylansnow/vimba_pose_detection/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dylansnow/vimba_pose_detection.svg?style=for-the-badge
[forks-url]: https://github.com/dylansnow/vimba_pose_detection/network/members
[stars-shield]: https://img.shields.io/github/stars/dylansnow/vimba_pose_detection.svg?style=for-the-badge
[stars-url]: https://github.com/dylansnow/vimba_pose_detection/stargazers
[issues-shield]: https://img.shields.io/github/issues/dylansnow/vimba_pose_detection.svg?style=for-the-badge
[issues-url]: https://github.com/dylansnow/vimba_pose_detection/issues
[license-shield]: https://img.shields.io/github/license/dylansnow/vimba_pose_detection.svg?style=for-the-badge
[license-url]: https://github.com/dylansnow/vimba_pose_detection/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png