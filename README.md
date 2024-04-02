# sms_spam_detector

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, I refactor code from an SMS text classification solution into a function that constructs a SVC and Tfidf-Vectorizer pipeline. The goal is to create a streamlined and efficient process for classifying SMS messages as spam or not spam. Additionally, we will create a Gradio app to host the application, enabling users to test text messages and receive immediate feedback on whether the text is classified as spam or not.

## Features

- Pipeline Model: Develop a SVC and Tfidf-Vectorizer pipeline to classify SMS messages as spam or not spam.
- Model Refactoring: Refactor existing code into a function that constructs and trains the SVC and Tfidf-Vectorizer pipeline, ensuring modularity and reusability.
- Gradio App Integration: Integrate the trained model into a Gradio app, allowing users to input text messages and receive instant feedback on whether the message is classified as spam or not.
- User-Friendly Interface: Design a user-friendly interface for the Gradio app, providing clear instructions and intuitive interaction for users testing text messages.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Gradio

### Installation

1. Clone the repository to your local machine:

```bash
git clone git@github.com:LardexTheLarge/sms_spam_detector.git
```

2. Navigate to the project directory:

```bash
cd sms_spam_detector
```

3. Install the required dependencies and models in the first cell.

## Usage

1. Refactor the existing code into a function that constructs and trains the pipeline.
2. Create a Gradio app to host the application, enabling users to test text messages and receive feedback on whether the text is classified as spam or not.
3. Test the Gradio app with sample text messages to ensure proper functionality and performance of the pipeline.

## Documentation

The code is documented with inline comments to explain its functionality. You can refer to the comments in the code for details on how it works.

## Contributing

Contributions are not allowed for this project.

## License

This project is licensed under the MIT License.
