<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
 
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->

[![Contributors](https://img.shields.io/github/contributors/username/repository.svg?style=flat-square)][contributors-url]
[![Forks](https://img.shields.io/github/forks/username/repository.svg?style=flat-square)](https://github.com/fasih0001/ParallelVision/fork)
[![Stars](https://img.shields.io/github/stars/username/repository.svg?style=flat-square)](https://github.com/fasih0001/ParallelVision/stargazers)
[![Issues](https://img.shields.io/github/issues/username/repository.svg?style=flat-square)](https://github.com/fasih0001/ParallelVision/issues)
[![License](https://img.shields.io/github/license/username/repository.svg?style=flat-square)](https://github.com/fasih0001/ParallelVision/blob/main/LICENSE)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue.svg?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/syed-m-fasih-ul-hassan-00426117b/)



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Parallel Vision: Enhancing Parallel CNN Processing on Resource Constraint Systems</h3>

  <p align="center">
    An impressive open-source project <br> focused on One CNN per Core Approach <br> for  <br> resource-constrained systems. 
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
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

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This open-source project invites collaboration and contributions from the community to enhance the Y-Net architecture. Y-Net enables the parallel execution of convolutional neural networks (CNNs) on resource-constrained systems, addressing the challenges of limited computational resources.

As an open-source initiative, the project encourages individuals to share ideas, assess feasibility, and contribute to the codebase. By leveraging the collective expertise of researchers, developers, and enthusiasts, we can drive the evolution of Y-Net. Contributions may include code optimizations, algorithm enhancements, and additional features tailored to resource-constrained environments.

Join us in this collaborative effort to explore innovative approaches, experiment with novel techniques, and create more efficient deep learning solutions. Together, we can push the boundaries of CNN execution on resource-constrained systems and pave the way for practical and scalable applications in diverse domains.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With


*[![TensorFlow](https://img.shields.io/badge/-TensorFlow-orange?logo=tensorflow&logoColor=white&style=flat-square)][Next-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

The Y-Net architecture is designed to run two Convolutional Neural Networks (CNNs) in parallel using the One CNN per Core approach. This approach is particularly useful in resource-constrained systems where multiple CNNs need to be executed simultaneously.

### Prerequisites

Before diving into the project, make sure you have the following prerequisites installed on your system:

1. Python (version 3.6 or above)
1. TensorFlow (version 2.0 or above)
1. Any additional dependencies or libraries specific to your implementation

### Installation

To install the necessary dependencies, follow these steps:

1. Create a new virtual environment (optional but recommended):
```sh
python3 -m venv ynet-env
source ynet-env/bin/activate
```
3. Clone the repo
   ```sh
   git clone https://github.com/fasih0001/ParallelVision.git
   ```
3. Install TensorFlow:
   ```sh
   pip install tensorflow
   ```
4. Install any other required dependencies:
   ```sh
   pip install numpy
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

To use the Y-Net architecture, follow these steps:
1.Open core1/model.py and core2/model.py files to implement the CNN models for each core. Customize the architecture, layers, and training logic based on your requirements.
1. In the main.py file, you can create instances of the CNN cores and orchestrate the parallel execution. Here's a basic example:
```py
from core1.model import Core1Model
from core2.model import Core2Model

# Instantiate the models
core1 = Core1Model()
core2 = Core2Model()

# Train or perform other operations on the cores
core1.train()
core2.predict()
```

1. You can expand upon this example to include data loading, preprocessing, and any additional functionality you need for your project.
```sh
python main.py
```
This will execute your Y-Net architecture, running the two CNN cores in parallel.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Conclusion
Congratulations! You have completed the initial setup and can now start exploring and expanding the Y-Net architecture. Feel free to modify, experiment, and optimize the architecture according to your specific use case.

Remember to refer to the TensorFlow documentation and other relevant resources to further enhance your understanding of neural networks and parallel computing.

Happy coding!

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

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com) 
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


[Next-url]: [https://www.tensorflow.org/]()
[contributors-url]: [https://github.com/fasih0001/ParallelVision/graphs/contributors]()
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links 
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/fasih0001/ParallelVision/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/fasih0001/ParallelVision/fork
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: [https://nextjs.org/](https://www.tensorflow.org/)
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
-->

