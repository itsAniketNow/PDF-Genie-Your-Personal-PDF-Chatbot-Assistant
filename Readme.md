# PDF Genie: Your Personal PDF Chatbot Assistant
PDF Genie is a strong conversational AI program that helps users extract information from numerous PDF documents and answer queries based on the context. With its user-friendly interface and advanced AI capabilities, PDF Genie makes it simple to interact with PDF documents and receive important information.

## Project Description
PDF Genie is written in Python and uses cutting-edge machine learning and natural language processing techniques. The application uses the Google Gemini model for training, but users can easily choose between models provided by OpenAI and Hugging Face. PDF Genie, created with Streamlit, provides a smooth user experience by allowing users to upload multiple PDF files, extract content, and engage in engaging conversations with the chatbot.

## Technology Used
- Python: The core programming language used for development.
- Streamlit: A powerful framework for building interactive web applications with Python.
- Machine Learning (ML) / Deep Learning (DL): Advanced techniques employed for training the AI models.
- Natural Language Processing (NLP): Techniques used to understand and process natural language input.
- Google Gemini Model: The primary AI model used for training and inference.
- OpenAI and Hugging Face Models: Additional AI models available for users to choose from.
- VS Code: Integrated Development Environment (IDE) used for coding and project management.

## Features
- PDF Upload: Users can upload multiple PDF files.
- Text Extraction: Extracts text from uploaded PDF files.
- Conversational AI: Utilizes AI models to answer user questions.
- Chat Interface: Provides an interactive chat interface for user-bot interactions.

## Getting Started
To run PDF Genie locally on your machine, follow these steps:

Clone the Repository:

```
git clone (https://github.com/itsAniketNow/PDF_Chatbot/new/main)
```
Install Dependencies:

```
pip install -r requirements.txt
```

#### Set up API Keys:

Obtain API keys for Google, OpenAI, or Hugging Face and set them in the .env file.
```
env
GOOGLE_API_KEY=your_google_api_key_here
OPENAI_API_KEY=your_openai_api_key_here
HUGGINGFACE_API_KEY=your_huggingface_api_key_here
```

### Run the Application:

```
streamlit run main.py
```
- Upload PDFs:

- Use the sidebar to upload PDF files.

- Engage with the Chatbot:

- Chat with the AI in the main interface and ask questions about the uploaded PDFs.

## Deployment
To deploy PDF Genie to the cloud, build the Docker image and push it to your registry. Consult Docker's documentation for detailed instructions on building and pushing Docker images.

## References
- Streamlit Documentation
- Google Gemini
- OpenAI
- Hugging Face

## Acknowledgments
- Google Gemini: For providing the underlying language model.
- Streamlit: For the user interface framework.
- Let PDF Genie be your ultimate assistant in navigating through PDF documents and extracting valuable insights with ease!
