
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="assets/logo_document.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Medical Abstract Classifier</h3>
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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project builds a natural language processing (NLP) model to automatically classify lines in medical research abstracts into their corresponding sections: Background, Objective, Methods, Results, or Conclusion.

* Uses token-level, character-level, and positional embeddings for deep contextual understanding.
* Incorporates custom feature engineering like line number and total lines to support positional encoding. 
* Implements multi-input deep learning pipelines with TensorFlow and Keras.
* Acheived 83% accuracy.
* Uses the PubMed 20k RCT dataset.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
* [![TensorFlow][TensorFlow]][TensorFlow-url]
* [![Keras][Keras]][Keras-url]
* [![Python][Python]][Python-url]
* [![Pandas][Pandas]][Pandas-url]
* [![Matplotlib][Matplotlib]][Matplotlib-url]
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
### Prerequisites
1. TensorFlow 2.15.0 must be installed
    ```sh
    !pip install tensorflow==2.15.0 
    ```

2. TensorFlow Hub 2.15.0 must be installed
    ```sh
    tensorflow-hub keras==2.15.0
    ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/nithinkosanam/Medical-Abstract-Classifier.git
   cd Medical-Abstract-Classifier
   ```
2. Run the notebook (or run in colab)
   ```sh
   jupyter notebook
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[Python-url]: https://www.python.org/  
[Python]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=%23FFFFFF

[TensorFlow-url]: https://www.tensorflow.org/  
[TensorFlow]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=%23FFFFFF

[Pandas-url]: https://pandas.pydata.org/  
[Pandas]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white

[Matplotlib-url]: https://matplotlib.org/  
[Matplotlib]: https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white

[Keras-url]: https://keras.io/  
[Keras]: https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white
