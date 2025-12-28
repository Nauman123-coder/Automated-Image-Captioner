# 🌐 Automated Image Captioner

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Gradio](https://img.shields.io/badge/UI-Gradio-orange.svg)](https://gradio.app/)
[![Transformers](https://img.shields.io/badge/AI-Transformers-yellow.svg)](https://huggingface.co/docs/transformers/index)

An end-to-end AI application that automatically generates descriptive captions for images. This project features a **Gradio Web Interface** for manual interaction and a **URL Scraping Tool** for batch-processing images from news articles or Wikipedia pages.

## 🚀 Overview

This project was developed to explore the intersection of Computer Vision and Web Accessibility. By leveraging the **BLIP (Bootstrapping Language-Image Pre-training)** model, the tool converts visual data into human-readable text, which can be used as Alt-Text to assist visually impaired users and improve SEO for digital media.

### Key Features

* **Web App:** Upload images manually to get instant AI-generated captions via a Gradio UI.
* **URL Scraper:** Paste a website URL (e.g., a news article) to automatically extract and caption every image on the page.
* **Batch Export:** Saves all scraped captions into a structured `captions.txt` file.
* **Notebook Integration:** Includes a dedicated Jupyter Notebook for research and experimentation.

## 🛠️ Project Structure
```text
.
├── app.py                      # The main Gradio web application
├── automate_url_captioner.py   # Tool for scraping and captioning URLs
├── image_captioning.ipynb      # Notebook for experimental testing
├── requirements.txt            # Project dependencies
├── .gitignore                  # Files to exclude from Git
└── README.md                   # Project documentation
```

## ⚙️ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/Nauman123-coder/Automated-Image-Captioner.git
cd Automated-Image-Captioner
```

### 2. Set up the environment
```bash
python3 -m venv my_env
source my_env/bin/activate  # On Windows use: my_env\Scripts\activate
pip install -r requirements.txt
```

### 3. Run the Web App
```bash
python3 app.py
```

### 4. Run the URL Scraper
```bash
python3 automate_url_captioner.py
```

## 🧠 About the Model

This project uses the **Salesforce BLIP-base** model. BLIP (Bootstrapping Language-Image Pre-training) is a unified vision-language framework that excels at understanding and generating text based on visual inputs, even when dealing with noisy web data.

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!
