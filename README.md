
<!-- PROJECT LOGO -->
<a id="readme-top"></a>
<br />
<div align="center">
  <a>
    <img src="assets/logo_document.png" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">Medical Abstract Classifier</h1>
</div>




<!-- ABOUT THE PROJECT -->
## About The Project

This project builds a natural language processing (NLP) model to automatically classify lines in medical research abstracts into their corresponding sections: Background, Objective, Methods, Results, or Conclusion.

* Uses token-level, character-level, and positional embeddings for deep contextual understanding.
* Incorporates custom feature engineering like line number and total lines to support positional encoding. 
* Implements multi-input deep learning pipelines with TensorFlow and Keras.
* Acheives 83% accuracy.
* Uses the PubMed 20k RCT dataset.


## Built With
* [![TensorFlow][TensorFlow]][TensorFlow-url]
* [![Keras][Keras]][Keras-url]
* [![Python][Python]][Python-url]
* [![Pandas][Pandas]][Pandas-url]
* [![Matplotlib][Matplotlib]][Matplotlib-url]



<!-- GETTING STARTED -->
## Getting Started
1. Paste the following link into your browser to open the notebook in colab, then press **"Run All"**
    ```sh
    https://colab.research.google.com/github/nithinkosanam/Medical-Abstract-Classifier/blob/main/medical_abstract_classifier.ipynb
    ```
2. Colab will ask you to restart the session, click **"Restart Session"** and then press **"Run All"** 



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
