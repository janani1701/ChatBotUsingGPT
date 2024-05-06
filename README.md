# AI-Powered Chatbot Development and Performance Analysis

## Overview
This repository contains the code and documentation for developing an AI-powered chatbot using Python, Pandas, OpenAI's GPT-3.5 language model, Flask, HTML, CSS, and JavaScript. The chatbot is designed to interact with users, process queries, and provide responses based on predefined guidelines. Additionally, performance analysis metrics are implemented to evaluate the chatbot's accuracy and processing efficiency.

## Contents
1. [Description](#description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Performance Analysis](#performance-analysis)
5. [Contributing](#contributing)

## Description
The project comprises several levels of development, each focusing on different aspects of chatbot functionality and performance evaluation.

### Level 1: Model Integration and Initial Data Querying
- Library Selection: Install necessary libraries including OpenAI for GPT-3.5 language model integration and Pandas for dataset manipulation. Utilize the 'lanchain_experimental' library for simplified interaction with the language model through dataframes.
- Data Preparation & Querying: Clean and prepare the dataset using Pandas, ensuring compatibility with the language model.
- Model Integration: Establish connectivity to the GPT-3.5 language model using OpenAI library and configure the API key for authentication.

### Level 2: Chatbot Interface Development and Query Handling
- Library Selection: Install Flask for setting up a web application to handle user queries and responses.
- Flask Application Setup and Endpoint Definition: Initialize a Flask application and define endpoints for query processing. Implement dynamic interaction through HTML, CSS, and JavaScript to create an interactive chatbot interface.
  
### Level 3: Dynamic Instruction Manual for Adaptive Responses
- Reading Instruction File: Read guidelines and rules from an 'Instructions.txt' file to be followed by the chatbot.
- Creating Prefix: Use extracted instructions to create a prefix variable for contextual guidance.
- Creating Pandas DataFrame Agent: Utilize the Langchain library to create a Pandas DataFrame agent incorporating the predefined prefix for generating responses consistent with the guidelines.

## Installation
1. Clone this repository to your local machine.
2. Install the required libraries.
3. Ensure you have an OpenAI API key for GPT-3.5 model integration.

## Usage
1. Run the Flask application using `python app.py`.
2. Access the chatbot interface through the provided HTTP link.
3. Input queries and interact with the chatbot.
4. Evaluate performance metrics through the implemented functionality.

## Performance Analysis
- Track processing time and evaluate response accuracy using the provided endpoints.
- Assess performance metrics to gain insights into the chatbot's efficiency and effectiveness in handling user queries.

## Contributing
Contributions are welcome! Please feel free to open issues or pull requests for any improvements or bug fixes.
