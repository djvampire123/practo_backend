# Practo - Expiry Date Detection & Pill Image Reconstruction API

Practo is a robust API designed to assist users in managing their health by providing key functionalities like expiry date detection for products and image reconstruction for various medications. This project leverages advanced machine learning and image processing techniques to extract and process crucial information from product images.

## Features

- **Expiry Date Detection:** Automatically detects the expiry date from product packaging using OCR and advanced text recognition.
- **Pill Image Reconstruction:** Reconstructs images of pills to help users identify and verify medications through visual aids.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

```bash
python -m pip install -r requirements.txt
```

**Installation**
A step by step series of examples that tell you how to get a development environment running:

Clone the repository:
```bash
git clone https://github.com/your-username/practo.git
cd practo
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Set up environment variables:
Ensure you have the necessary API keys and other configurations set up in your environment.
Run the server:
```bash
python server.py
```
**Usage**
To use the API, send a POST request to the endpoint with an image of the product or pill:

```curl
curl -X POST -F "image=@path_to_your_image.jpg" http://localhost:8000/predict
```
**Built With**

Tornado - The web framework used
OpenCV - Image processing library
Google Cloud Vision API - Used for OCR and text detection

**License**
This project is licensed under the MIT License - see the LICENSE.md file for details
