# Chat With Multiple PDFs

This project, **Chat With Multiple PDFs**, is a user-friendly application that allows users to interact with the contents of multiple PDF files conversationally. Using the power of Google Gemini API and LangChain, this app processes and understands text from PDFs, enabling dynamic Q&A and discussion around the uploaded documents. The user interface is built with Streamlit and deployed on Streamlit Cloud, making it easy to access and navigate for seamless interaction.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Multiple PDF Support**: Upload and interact with multiple PDFs simultaneously.
- **Conversational Interface**: Powered by LangChain and Google Gemini API to facilitate question-answering based on PDF content.
- **User-Friendly UI**: Streamlit-based interface for simple and intuitive navigation.
- **Quick Setup and Deployment**: Easy deployment on Streamlit Cloud, allowing access from any browser.

## Demo

You can view the app on Streamlit Cloud: [Live Demo](https://chat-with-pdf-document.streamlit.app/)

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ayush-ak87/Chat-With-PDF.git
   cd Chat-With-PDF
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up Google Gemini API credentials**:
   - Obtain your API key from the Google Gemini platform.
   - Save the API key to a `.env` file in the root directory:
     ```plaintext
     GOOGLE_GEMINI_API_KEY=your_api_key_here
     ```

5. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Upload PDFs**: Start by uploading one or more PDF files.
2. **Ask Questions**: Type questions related to the content of the PDFs, and the app will generate responses based on document analysis.
3. **Clear or Reset**: Reset the session to upload new documents and start a new conversation.

## Configuration

Ensure that you have the following environment variables set in the `.env` file:

- `GOOGLE_GEMINI_API_KEY`: Your Google Gemini API key.
- Other relevant configurations may be added depending on customization needs.

## Dependencies

The primary libraries and tools used in this project include:

- **LangChain**: For building conversational chains over the text.
- **Google Gemini API**: Provides the language model for understanding and responding based on PDF contents.
- **Streamlit**: Powers the interactive web interface.

Full dependencies are listed in the `requirements.txt` file.

## Examples

Here are a few example questions you can try in the app:

- **"Summarize the main points of this document."**
- **"What is the significance of the data presented on page 3?"**
- **"List key insights regarding [topic]."**

These types of queries allow the app to demonstrate its NLP capabilities in understanding and parsing PDF content.

## Troubleshooting

- **Issue with API Key**: If you encounter issues related to the Google Gemini API, ensure that the API key is valid and properly set in the `.env` file.
- **PDF Parsing Errors**: If the app has trouble processing certain PDFs, verify the format and check for any encryption that might block parsing.
- **UI Not Loading Properly**: Check that Streamlit is correctly installed and that the app is running on the correct port.

## Contributing

We welcome contributions! Please fork the repository, make your changes, and submit a pull request. Before contributing, check for open issues or create a new one to discuss any significant changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to explore the [GitHub Repository](https://github.com/Ayush-ak87/Chat-With-PDF) for further details and updates.
