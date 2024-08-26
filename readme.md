# IMDB Movie Review Sentiment Analysis

This project provides a sentiment analysis tool for movie reviews using a pre-trained RNN model with TensorFlow and Keras. It utilizes a Streamlit interface to allow users to input movie reviews and receive sentiment classifications as output.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributing](#contributing)

## Overview

The sentiment analysis tool is designed to classify IMDB movie reviews into positive or negative categories. The application is built using TensorFlow for modeling and Streamlit for the web interface, providing an interactive and user-friendly environment for real-time sentiment analysis.

## Features

- **Sentiment Classification**: Classifies the sentiment of movie reviews as either positive or negative.
- **Interactive Web Interface**: Uses Streamlit to provide a simple and interactive web interface.
- **Pre-trained RNN Model**: Leverages a pre-trained RNN model to predict the sentiment based on text input.

## Installation

### Prerequisites

- Python 3.8+
- Git

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/imdb-sentiment-analysis.git
   cd imdb-sentiment-analysis
    ```
2. **Create a virtual environment:**
``` bash 
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. **Install the required dependencies:**
``` bash
pip install -r requirements.txt
```

4.**Set up environment variables:** Copy the `.env.example` file to create a `.env` file and adjust the variables accordingly.

## Usage
To start the application, run:

``` bash 
streamlit run app.py
```
Navigate to the provided local web address to interact with the application.

## Project Structure
-`app.py`: Main application file for the Streamlit interface.
-`simple_rnn_imdb.h5`: Pre-trained RNN model file.
-`requirements.txt`: Lists all the necessary Python libraries.
-`.env`: Contains environment variables (ensure this file is not tracked by Git).
-`.gitignore`: Specifies intentionally untracked files to ignore.
Dependencies

## Dependencies include:

`tensorflow`
`pandas`
`numpy`
`scikit-learn`
`matplotlib`
`tensorboard`
`streamlit`
`keras`
`scikeras`
`nltk`
These can be found in the requirements.txt file.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contributing
Contributions are welcome! If you have suggestions for improvements or have encountered issues, please open an issue or submit a pull request.