# Chat With Multiple PDF

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/Ayush-ak87/Chat-With-PDF)

## Overview
"Chat With Multiple PDF" is a web-based application that enables users to engage in interactive conversations with the content of multiple PDF documents simultaneously. Built using **Google Gemini API** and **LangChain**, this tool allows users to query PDF content efficiently and gain insights without manual reading. The web app interface is developed using **Streamlit** and deployed on **Streamlit Cloud** for easy access and scalability.

## Key Features
- **Multi-PDF Interaction:** Seamlessly upload and interact with multiple PDF files at once.
- **Smart Querying:** Uses advanced NLP models to provide accurate responses to user queries about the PDF content.
- **Streamlit Web App:** Intuitive web interface built with Streamlit for enhanced user experience.
- **Cloud Deployment:** Deployed on Streamlit Cloud for accessible, real-time interaction.

## Project Workflow
1. **PDF Upload:** Users can upload one or more PDF documents.
2. **Content Parsing:** The application parses the PDF content and prepares it for query interaction.
3. **Query Processing:** 
   - Uses Google Gemini API and LangChain for processing user queries.
   - Delivers relevant responses based on content across all uploaded PDFs.
4. **Response Display:** Displays answers and relevant portion directly in the Streamlit app.

## Technologies Used
- **APIs and Frameworks:** Google Gemini API, LangChain
- **Frontend:** Streamlit
- **Deployment Platform:** Streamlit Cloud
- **Programming Language:** Python

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Ayush-ak87/Chat-With-PDF.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Chat-With-PDF
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Access the app and upload PDF documents.
2. Enter questions or prompts related to the content of the PDFs.
3. Receive contextual responses based on the PDF content.

## Future Enhancements
- Add support for more file types (e.g., Word documents).
- Integrate further analytics on document content.
- Enhance response relevance by incorporating user feedback.

## Contributing
Contributions are welcome! Feel free to submit a pull request or raise an issue.

## License
This project is licensed under the MIT License.

--- 
