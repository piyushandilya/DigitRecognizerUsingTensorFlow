[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Digit Recognizer Using Keras</h3>

  <p align="center">
    Basic Hand Written Digit Recognizer using Keras
    <br />
    <a href="https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow">View Demo</a>
    ·
    <a href="https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/issues">Report Bug</a>
    ·
    <a href="https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/issues">Request Feature</a>
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
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/blob/main/DigitRecognizer.jpg?raw=true)

This is a CNN based model that trains on the input images of handwritten digits and predicts the ouput with maximum accuracy for new hand written digit images.

### Built With

* [Python3.7.3](https://www.python.org/downloads/)
* [Keras](https://keras.io/)
* [Tensorflow](https://www.tensorflow.org/)
* [Matplotlib](https://matplotlib.org/)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites


* Python
* Pip (to install Keras)
* Keras
* Tensorflow

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow.git
   ```
2. Run


<!-- USAGE EXAMPLES -->
## Usage

1. Just run the code normally and let the model<br>
  a) Load pre-shuffled image data from the MNIST datasets<br>
  b) Process/Reshape the input data to train<br>
  c) Normalize the data<br>
  d) Convert the training labels to categorical data<br>
  e) Compile and fit on the training data<br>
  f) and evaluate on the test data, printing the accuracy on both the training and the test data<br>
  g) The model will loop and display the test images and predict the output for those images<br>



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/issues) for a list of proposed features (and known issues).



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

Piyush Shandilya - [@piyushandilya](https://twitter.com/piyushandilya) - piyushshandilya44@gmail.com

Project Link: [https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow](https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [MNIST](http://yann.lecun.com/exdb/mnist/)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/piyushandilya/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/piyushandilya/repo.svg?style=for-the-badge
[forks-url]: https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/network/members
[stars-shield]: https://img.shields.io/github/stars/piyushandilya/repo.svg?style=for-the-badge
[stars-url]: https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/stargazers
[issues-shield]: https://img.shields.io/github/issues/piyushandilya/repo.svg?style=for-the-badge
[issues-url]: https://github.com/piyushandilya/DigitRecognizerUsingTensorFlow/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/piyush-shandilya-7b857577
[product-screenshot]: images/DigitRecognizerm.gif
