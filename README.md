# Text Summarization with distilbart-cnn-12-6

This repository contains a Python script that demonstrates how to perform text summarization using the shleifer/distilbart-cnn-12-6 model provided by the Hugging Face Transformers library. The code utilizes the Hugging Face API for text summarization and integrates it with a user-friendly web-based interface using the Gradio library.

## Image1

<img width="479" alt="Screenshot 2023-08-19 215538" src="https://github.com/yunus5603/Text_Summarization_App/assets/60473468/d862b9e2-203c-4797-975c-a59276df7dc9">

## Image2

<img width="470" alt="image" src="https://github.com/yunus5603/Text_Summarization_App/assets/60473468/5b8ce64e-b0e6-4968-a9e5-bc67527a2cb5">


## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Web Interface](#web-interface)
- [License](#license)

## Introduction
  
Text summarization is a natural language processing task that involves condensing a longer document or piece of text into a shorter version while preserving its key information. This repository demonstrates how to use the shleifer/distilbart-cnn-12-6 model for text summarization using the Hugging Face Transformers library.

## Requirements

Before running the code, make sure you have the following dependencies installed:

- Python 3.x
- Hugging Face Transformers library
- Gradio library
- IPython
- dotenv
  
You can install the required dependencies using the following command:

```bash
pip install transformers gradio ipython python-dotenv
```
## Installation

To use this code, you need to perform the following steps:

Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/your-repo.git
```
Navigate to the project directory:
```bash
cd your-repo
```
Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
Install the project dependencies:
```bash
pip install -r requirements.txt
```
## Usage

To run the text summarization script, execute the following command:
```bash
python text_summarization.py
```
This script demonstrates how to use the shleifer/distilbart-cnn-12-6 model to generate summaries for input text.

## Web Interface

The repository also includes a web-based interface for easy interaction with the summarization model. To launch the web interface, use the following command:
```bash
python web_interface.py
```
The web interface allows you to input a text and receive a summarized version using the shleifer/distilbart-cnn-12-6 model. This interface leverages the Gradio library to create a user-friendly interaction experience.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
