# Final Project

## Emotion Detection Application

This project is a web-based Emotion Detection Application developed using Python and Flask. The application uses the Watson NLP Emotion Prediction service to analyze text and identify emotions.

### Supported Emotions

The application detects the following emotions:

* Anger
* Disgust
* Fear
* Joy
* Sadness

It also identifies the dominant emotion in the provided text.

## Project Structure

```text
oaqjp-final-project-emb-ai
│
├── EmotionDetection
│   ├── __init__.py
│   └── emotion_detection.py
│
├── static
│   └── mywebscript.js
│
├── templates
│   └── index.html
│
├── server.py
├── test_emotion_detection.py
├── README.md
└── LICENSE
```

## Features

* Emotion detection using Watson NLP
* Flask web interface
* Unit testing support
* Error handling for invalid input
* Static code analysis using Pylint
* Modular package structure

## Installation

Clone the repository:

```bash
git clone https://github.com/darshakj07/oaqjp-final-project-emb-ai.git
```

Move into the project directory:

```bash
cd oaqjp-final-project-emb-ai
```

Install required packages:

```bash
pip install flask requests pylint
```

## Running the Application

Start the Flask application:

```bash
python3 server.py
```

Open the application in your browser and enter text to analyze emotions.

## Running Unit Tests

```bash
python3 test_emotion_detection.py
```

## Running Static Code Analysis

```bash
pylint server.py
```

Expected result:

```text
Your code has been rated at 10.00/10
```

## Technologies Used

* Python
* Flask
* Requests
* Watson NLP
* GitHub
* Pylint

## Author

Darshak Jikadra
