# PDF Chatbot using OpenAI GPT-3.5
This project demonstrates how to build a chatbot that interacts with the OpenAI GPT-3.5 model by first extracting text from a PDF file using the PyPDF2 library. The chatbot reads the content of the PDF and responds to user questions by referencing the extracted text.



## Features

- Extract text from PDF files using PyPDF2.
- Chat with OpenAI's GPT-3.5 model, incorporating the PDF content into the conversation.
- User-friendly interaction with continuous prompts.
- Handles file input errors (e.g., missing or incorrect PDF paths).


## Installation

Clone the repository:
```
git clone https://github.com/Umairyousaf0098/chatwithpdf.git
```


    
## Requirements
To run this project, you'll need the following dependencies:
- Python 3.x
- OpenAI Python client (openai)
- PyPDF2 for PDF text extraction
You can install the necessary dependencies using the following command:
```
pip install -r requirements.txt
```

## Environment Variables
This project requires an environment variable for the OpenAI API key. Create a .env file in the project root directory with the following content:
```
OPEN_AI_KEY="YOUR API KEY HERE"
```
## How to Obtain OpenAI API Key
1. Visit the [OpenAI Website](https://platform.openai.com/api-keys).
2. Sign up for an account if you don’t have one already.
3. Navigate to the API section from your dashboard.
4. Generate a new API key and copy it.
5. Paste the API key into your .env file as mentioned above.

## Run Locally

After cloning the repository and installing the requirements, navigate to the project directory.

Start the server witht the command below.

```
python app.py
```

