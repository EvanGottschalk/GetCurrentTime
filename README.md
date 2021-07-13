[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/EvanGottschalk/GetCurrentTime">
    <img src="images/logo.png" alt="Logo" width="151" height="80">
  </a>

  <h3 align="center">GetCurrentTime</h3>

  <p align="center">
    A simple program for retrieving and converting time data to be more legible
    <br />
    <a href="https://github.com/EvanGottschalk/GetCurrentTime"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/EvanGottschalk/GetCurrentTime">View Demo</a>
    ·
    <a href="https://github.com/EvanGottschalk/GetCurrentTime/issues">Report Bug</a>
    ·
    <a href="https://github.com/EvanGottschalk/GetCurrentTime/issues">Request Feature</a>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)


### Built With

`Python`


<!-- GETTING STARTED -->
## Getting Started

Simply run or import `GetCurrentTime` to gain access to all of its functions.

### Prerequisites

`GetCurrentTime` uses the `datetime`, `sched`, and `time` libraries, which are all default libraries of `Python`.

### Installation

1. Download `GetCurrentTime.py`

2. Congratulations! You're basically done. You may either run `GetCurrentTime.py` to use its functions, or import it into other code.



<!-- USAGE EXAMPLES -->
## Usage

`GetCurrentTime` is useful for any program where accurately keeping track of time is important.

Example 1: You or your program needs to know how many seconds have passed in the current minute.
```sh
GCT = GetCurrentTime()
seconds = GCT.getSecondString()
```

Example 2: You or your program needs to know the date 1000 days after 4/20/2022.
```sh
GCT = GetCurrentTime()
new_date = GCT.increaseDate('04202022', 1000)
```

Example 3: You or your program has a timestamp, and you want to know what time it actually represents in MM/DD/YYYY format.
```sh
GCT = GetCurrentTime()
date_time = convert_TimeStampToDateTime(timestamp)
```


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/EvanGottschalk/GetCurrentTime/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Evan Gottschalk - [Evan on LinkedIn](https://www.linkedin.com/in/evan-gottschalk/) - [@Fort1Evan](https://twitter.com/Fort1Evan) - magnus5557@gmail.com

Project Link: [https://github.com/EvanGottschalk/GetCurrentTime](https://github.com/EvanGottschalk/GetCurrentTime)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Thinking about contributing to this project? Please do! Your Github username will then appear here.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/EvanGottschalk/GetCurrentTime.svg?style=for-the-badge
[contributors-url]: https://github.com/EvanGottschalk/GetCurrentTime/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/EvanGottschalk/GetCurrentTime.svg?style=for-the-badge
[forks-url]: https://github.com/EvanGottschalk/GetCurrentTime/network/members
[stars-shield]: https://img.shields.io/github/stars/EvanGottschalk/GetCurrentTime.svg?style=for-the-badge
[stars-url]: https://github.com/EvanGottschalk/GetCurrentTime/stargazers
[issues-shield]: https://img.shields.io/github/issues/EvanGottschalk/GetCurrentTime.svg?style=for-the-badge
[issues-url]: https://github.com/EvanGottschalk/GetCurrentTime/issues
[license-shield]: https://img.shields.io/github/license/EvanGottschalk/GetCurrentTime.svg?style=for-the-badge
[license-url]: https://github.com/EvanGottschalk/GetCurrentTime/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/EvanGottschalk
