<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo, twitter_handle, email
-->





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
<p align="left">

  <h1 align="left">IoT Sensor Motion Predictor</h1>

  <p align="left">
    Predict the presence of human beings in a room using IoT sensor devices.
    <br />
    <a href="https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor">View Demo</a>
    ·
    <a href="https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/issues">Report Bug</a>
    ·
    <a href="https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Data Exploration](#exploration)
  * [Extract Transform Load](#etl)
  * [Model definition, training, and evaluation](#model)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
This is a **Data Science** project using [Environmental Sensor Telemetry Data](https://www.kaggle.com/garystafford/environmental-sensor-data-132k).<br>
This project consists of *data analysis*, *model definition* and *model training and evaluation* using various data science packages. 


### Built With

* [Apache Spark](https://spark.apache.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Apache Parquet](https://parquet.apache.org/)
* [Keras](https://keras.io/)
* [Tensorflow](https://www.tensorflow.org/)
* [Sci-Kit Learn](https://scikit-learn.org/)
* [Pandas](https://pandas.pydata.org/)



<!-- GETTING STARTED -->
## Getting Started

The project consists of three stages:
1. Data Exploration
2. Extract Transform Load
3. Model definition, training, and evaluation

The .ipynb (Jupyter Notebook) files contain the three stages of the project.

## Data exploration

Data Exploration refers to the initial exploration of the dataset along with subtle data analysis to obtain a vague idea about the dataset.<br>
This consists of statistical description, correlation matrix, box plots, etc.

## Extract Transform Load
 
Extract Transform Load (ETL) refers to the process of copying data from one or more sources into a destination system which represents the data differently from the source or in a different context than the source.<br>
It also involves transforming the data, feature engineering, detailed data analysis and improving the overall quality of the data.

## Model definition, training, and evaluation
 
Model definition refers to the process of choosing the models those are best suited for the dataset, along with the initial hyperparameters.<br>
Model training refers to the process of fitting the models to the training data.<br>
Model evaluation refers to the process of evaluating the process of the models using certain appropriate evaluation metrics and tuning the hyperparameters again based on the results.<br>
<br>
It is an iterative process until required performance is obtained. 



<!-- USAGE EXAMPLES -->
## Usage

This model can be used at situations where cameras and proximity sensors are not available to determine if there is a human being nearby.<br>
The model uses various other factors such as:
* Temperature
* Humidity
* Smoke
* Light

to determine if there is a human being in proximity.


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/issues) for a list of proposed features (and known issues).



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

Soundar Murugan - [@soundarzozm](https://twitter.com/soundarzozm)<br>
E-Mail - [soundarmurugan91@gmail.com](soundarmurugan91@gmail.com)

Project Link: [https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor](https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Gary A. Stafford](https://www.kaggle.com/garystafford) for providing the dataset for public use.
* [Romeo Kienzler](https://www.linkedin.com/in/romeo-kienzler-089b4557/) for providing motivation, education and inspiration for the project.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/soundarzozm/Iot-Sensor-Motion-Predictor.svg?style=flat-square
[contributors-url]: https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/soundarzozm/Iot-Sensor-Motion-Predictor.svg?style=flat-square
[forks-url]: https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/network/members
[stars-shield]: https://img.shields.io/github/stars/soundarzozm/Iot-Sensor-Motion-Predictor.svg?style=flat-square
[stars-url]: https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/stargazers
[issues-shield]: https://img.shields.io/github/issues/soundarzozm/Iot-Sensor-Motion-Predictor.svg?style=flat-square
[issues-url]: https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/issues
[license-shield]: https://img.shields.io/github/license/soundarzozm/Iot-Sensor-Motion-Predictor.svg?style=flat-square
[license-url]: https://github.com/soundarzozm/Iot-Sensor-Motion-Predictor/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/soundar-murugan
