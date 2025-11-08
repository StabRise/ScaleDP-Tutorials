<p align="center">
  <br/>
    <a href="https://stabrise.com/scaledp/" target="_blank"><img alt="ScaleDP" src="https://raw.githubusercontent.com/StabRise/ScaleDP/refs/heads/master/images/scaledp.webp" width="450" style="max-width: 100%;"></a>
  <br/>
</p>

<p align="center">
    <i>An Open-Source Library for Processing Documents in Apache Spark.</i>
</p>

<p align="center">
    <a href="https://pypi.org/project/scaledp/" alt="Package on PyPI"><img src="https://img.shields.io/pypi/v/scaledp.svg" /></a>
    <a href="https://github.com/stabrise/spark-pdf/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/stabrise/spark-pdf.svg?color=blue"></a>
    <a href="https://stabrise.com"><img alt="StabRise" src="https://img.
shields.io/badge/powered%20by-StabRise-orange.svg?
style=flat&colorA=E1523D&colorB=blue"></a>
    <a href="https://scaledp.stabrise.com/en/latest/"><img src="https://app.readthedocs.org/projects/scaledp/badge/?version=latest" alt="Documentation Status"/></a>
</p>

# ScaleDP Tutorials

[ScaleDP](https://github.com/StabRise/scaledp/) is a library for processing documents using Apache Spark.
And this repository contains jupyter notebooks with tutorials and examples of usage ScaleDP library.

**Source Code**: <a href="https://github.com/StabRise/ScaleDP/" target="_blank">https://github.com/StabRise/ScaleDP</a>


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

### QuickStart and General Examples

| Chapter                              | Notebook                                                                                                                                                                           |
|--------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1: QuickStart with ScaleDP           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/1.QuickStart.ipynb)   |
| 5: Efficient read PDF with Spark PDF | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/5.WithSparkPdf.ipynb) |

### OCR Examples

| Chapter                           | Notebook                                                                                                                                                                      |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1: Example of usage different OCR | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/ocr/1.Ocr.ipynb) |

### Ner Examples
| Chapter             | Notebook                                                                                                                                                                         |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1: NER Examples     | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/ner/1.Ner.ipynb)    |
| 2: LLM NER Examples | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/ner/2.LLMNer.ipynb) |

### Object Detection Examples

| Chapter                | Notebook                                                                                                                                                                                                  |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1: YoloOnnxDetector    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/object-detection/1.YoloOnnxDetector.ipynb)   |
| 2: Face Detection      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/object-detection/2.FaceDetection.ipynb)      |
| 3: Signature Detection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StabRise/scaledp-tutorials/blob/master/object-detection/3.SignatureDetection.ipynb) |

### De-identification Examples

| Chapter                            | Notebook |
|------------------------------------|----------|
| 1: De-identification Text          |          |
| 2: De-identification Images        |          |
| 3: De-identification PDF Documents |          |
| 4: De-identification Dicom         |          |

## Local Run

### Requirements

- Python 3.11
- Apache Spark 3.5 or higher
- Java 8, 11
- Tesseract 5.0 or higher
- Jupyter Lab | Google Colab

![](./images/ner_visualize.png)

![](./images/ner_visualize_1.png)


