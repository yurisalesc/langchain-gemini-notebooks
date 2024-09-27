
# Chat with Spreadsheet using Google Generative AI

This project demonstrates how to integrate Google Generative AI capabilities into a Jupyter Notebook environment, allowing users to interact with spreadsheets and perform various AI-powered tasks.

## Features

- **Google Generative AI Integration**: Utilizes Google's generative AI models to process and respond to spreadsheet data.
- **Spreadsheet Handling**: Supports interaction with spreadsheets using `pandas` for data manipulation.
- **Environment Configuration**: Leverages `.env` files to securely store API keys.
- **Modular AI Tools**: Includes support for `langchain` and `chromadb` for enhanced language model operations.

## Requirements

Ensure you have the following installed:

- Python 3.x
- `pandas==2.1.4`
- `google-generativeai==0.7.2`
- `langchain`
- `chromadb`
- `python-dotenv`

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/chat-with-spreadsheet.git
   cd chat-with-spreadsheet
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Google API key:
   - Create a `.env` file in the root directory and add your API key:
     ```
     GOOGLE_API_KEY=your_google_api_key
     ```

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook chat_with_spreadsheet.ipynb
   ```

## Usage

- The notebook walks you through connecting to Google Generative AI and utilizing its services.
- Interact with your spreadsheet data by loading files and manipulating them using `pandas`.
