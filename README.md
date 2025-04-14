# 3RVision custom ML Model

A web application for image classification using machine learning. This is simple version of 3RVision model.

## About

This project is a Flask-based web application that uses TensorFlow and Keras to classify images. Users can upload images through a web interface and get instant classification results. You'll see the results in JSON format.

## Prerequisites

Before setting up the project, ensure you have:
- Python 3.10 installed on your system
- pip (Python package manager)
- Basic understanding of Python and web development
- Sufficient disk space for the ML model and dependencies

## Setup

1. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install required packages:
```bash
pip install -r requirements.txt
```


## Running the Application

1. Start the Flask server:
```bash
python app.py
```

2. Open your browser and go to:
```
http://localhost:5001
```

3. Upload an image to get classification results.

## Project Structure

- `app.py` - Main application code
- `static/` - Static files and uploads
- `templates/` - HTML templates
- `3RVision_2.keras` - Our custom trained model