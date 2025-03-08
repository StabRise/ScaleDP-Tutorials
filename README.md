<p align="center">
  <br/>
    <img alt="ScaleDP" src="https://stabrise.com/media/filer_public_thumbnails/filer_public/4a/7d/4a7d97c2-50d7-4b7a-9902-af2df9b574da/scaledplogo.png__1000x300_subsampling-2.webp" width="450" style="max-width: 100%;">
  <br/>
</p>

<p align="center">
    <i>An Open-Source Library for Processing Documents in Apache Spark.</i>
</p>

<p align="center">
    <a href="https://pypi.org/project/scaledp/" alt="Package on PyPI"><img src="https://img.shields.io/pypi/v/scaledp.svg" /></a>
    <a href="https://github.com/stabrise/spark-pdf/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/stabrise/spark-pdf.svg?color=blue"></a>
    <a href="https://stabrise.com"><img alt="StabRise" src="https://img.shields.io/badge/powered%20by-StabRise-orange.svg?style=flat&colorA=E1523D&colorB=007D8A"></a>
</p>


# ScaleDP Tutorials

[ScaleDP](https://github.com/StabRise/scaledp/) is a library for processing documents using Apache Spark.
And this repository contains jupyter notebooks with tutorials and examples of usage ScaleDP library.

ScaleDP includes the following features:

- Load PDF documents/Images
- Extract text from PDF documents/Images
- Extract text Images/PDF documents, OCR
- Zero-shot Data extraction from the Images/PDF documents using LLM
- Object detection over Images/PDF documents
- NER/LLM over Images/PDF documents 
- Visualize results on the images
- Compatible with Spark PDF Datasource

## Table of Contents

We advise to run all examples through Google Colab for the easiest setup. Google Colab allows you to run it for free. All examples were tested using Google Colab, so it should be the most stable platform. However, any other cloud provider or local run should work. 

| Chapter                           | Notebook                                                                                                                                                                           |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1: QuickStart with ScaleDP        | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/1.QuickStart.ipynb)   |
| 2: Example of usage different OCR | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/2.Ocr.ipynb)          |
| 3: NER Examples                   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/3.Ner.ipynb)          |
| 4: LLM NER Examples               | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/4.LLMNer.ipynb)       |
| 5: With Spark PDF                 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/5.WithSparkPdf.ipynb) |

## Local Run

### Requirements

- Python 3.11
- Apache Spark 3.5 or higher
- Java 8, 11
- Tesseract 5.0 or higher
- Jupyter Lab | Google Colab
