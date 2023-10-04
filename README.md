# CS589_Week3_HW2

Here is a GitHub README.md file generated from the information provided:

# Customer Support Email Generator

This is a web application that allows customers to generate automated emails in their selected language. 

## Features

- Allows customer to select a language
- Generates a sample customer comment about products
- Creates an email subject based on the comment 
- Summarizes the comment
- Analyzes sentiment of the comment
- Generates an email response containing:
   - Summary of the customer's comment
   - Response based on sentiment analysis and selected language
- Can translate the comment and email to selected language

## Usage

The interface allows the user to:

- Select a language from the dropdown menu
- Click the "Generate" button

This will:

- Generate a sample customer comment 
- Create an email subject
- Summarize the comment
- Analyze sentiment 
- Generate an email response

The user can also check the boxes to:

- Translate the generated comment
- Translate the generated email response

## Implementation 

The project is implemented using:

- Flask for the web framework
- HTML/CSS for frontend 
- Calls to OpenAI API for text generation and translation

The main files are:

- `app.py` - Flask application
- `index.html` - Main HTML template 
- `styles.css` - CSS styling

## Setup

To run the application:

- Clone the repository
- Install dependencies (`pip install -r requirements.txt`)
- Add OpenAI API key to `.env` file
- Run `python app.py`
- Go to `http://localhost:5000`

Dependencies:

- Flask
- python-dotenv
- openai

## Customization

The language options, UI text, and product content can be customized by modifying `index.html`.

New languages can be added by updating the dropdown menu.

The text generation prompts in `app.py` can be modified as needed.

