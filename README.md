# AI Custom Chatbot for E-Commerce Website

## Overview
This project is a custom AI-powered chatbot built using Python and integrated into a website using Flask and JavaScript. The chatbot uses an Artificial Neural Network (ANN) to process user queries and provide responses based on pre-trained data. It is designed to help answer questions about products, brands, and services in an e-commerce environment.

## Features
- **Natural Language Processing**: The chatbot processes and understands user input using NLP techniques.
- **Artificial Neural Network**: The chatbot is powered by a feed-forward neural network to provide accurate responses based on trained data.
- **Web Integration**: The chatbot is integrated into a website, making it accessible from any browser.
- **Response Based on Training**: The chatbot will respond with predefined answers if the question matches any of the trained data.
- **User-Friendly Interface**: Simple and interactive UI for easy communication with the chatbot.

## Technologies Used
- **Python**: The core language for building the chatbot logic.
- **Flask**: Web framework to deploy the chatbot on a website.
- **HTML/CSS/JavaScript**: For building the user interface and handling interactions with the chatbot.
- **PyTorch**: Library for building and training the Artificial Neural Network (ANN).
- **NLP**: Natural Language Processing techniques to understand user queries.

## Setup and Installation

### Prerequisites
Ensure that you have the following installed:
- **Python 3.x** 
- **pip** (Python package manager)

### Steps to Run the Application

1. **Clone the Repository**:
   First, clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
# 2. Create a Virtual Environment
python -m venv venv

# 3. Activate the Virtual Environment
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
# source venv/bin/activate

# 4. Install Dependencies
pip install Flask torch torchvision nltk

# 5. Download NLTK Data
python -c "import nltk; nltk.download('punkt'); quit()"

# 6. Train the Model
python train.py

# 7. Run the Chatbot
python chat.py

# 8. Install Flask for Web Deployment
pip install flask

# 9. Check Flask Installation
pip show flask

# 10. Run the Flask Web Application
python app.py
