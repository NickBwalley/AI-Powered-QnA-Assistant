# AI-Powered-QnA-Assistant

A powerful tool that allows users to ask questions about their PDF and DOCX files and receive contextually relevant answers using OpenAI's API.

## Overview

This application enables users to upload document files (.pdf or .docx) and ask questions about the content. The tool uses OpenAI's powerful language model to analyze the documents and provide accurate responses based on the context within those files.

## Features

- **Document Upload:** Supports PDF and DOCX files up to 200MB
- **Interactive Q&A:** Ask any question about your document and get contextually relevant answers
- **Simple Interface:** User-friendly design built with Streamlit
- **Fast Processing:** Quick analysis and response generation

## Demo

![Screenshot of Output](https://raw.githubusercontent.com/NickBwalley/AI-Powered-QnA-Assistant/master/assets/img1.png)



## Installation

### Prerequisites

- Python 3.7+
- OpenAI API key

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/NickBwalley/AI-Powered-QnA-Assistant.git
   cd AI-Powered-QnA-Assistant
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**
   
   - On Windows:
   ```bash
   venv\Scripts\activate
   ```
   
   - On macOS/Linux:
   ```bash
   source venv/bin/activate
   ```

4. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

5. **Create a .env file**
   
   Create a `.env` file in the root directory and add your OpenAI API key:
   ```
   OPENAI_APIKEY=your_api_key_here
   ```

## Usage

1. **Start the application**
   ```bash
   streamlit run app.py
   ```

2. **Upload a document**
   - Select a PDF or DOCX file (must be less than 200MB)
   - Wait for the file to process

3. **Ask questions**
   - Type your question in the text area
   - Receive an AI-generated answer based on the content of your document

## How It Works

1. The application processes and indexes the uploaded document
2. When you ask a question, the system:
   - Analyzes your question
   - Searches for relevant context within the document
   - Uses OpenAI's API to generate a comprehensive answer
   - Returns the response with accurate information from your document

## Limitations

- Document size limit: 200MB
- Currently supports only PDF and DOCX formats
- Response quality depends on the clarity of your question and the content of your document

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [OpenAI](https://openai.com/) for their powerful API
- [Streamlit](https://streamlit.io/) for the interactive web interface
- All contributors and supporters of this project

## Contact

Nick Bwalley - [@NickBwalley](https://github.com/NickBwalley)

Project Link: [https://github.com/NickBwalley/AI-Powered-QnA-Assistant](https://github.com/NickBwalley/AI-Powered-QnA-Assistant)
