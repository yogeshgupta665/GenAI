# Summarize Documents with LangChain & Pinecone

This is a Streamlit app that allows you to summarize documents using LangChain and Pinecone.

## Prerequisites
Before running this app, make sure you have the following:
- OpenAI API key
- Pinecone API key
- Pinecone environment
- Pinecone index name
- Source document in PDF format

## Installation
To run this code locally, you need to install the following dependencies:
- os
- tempfile
- streamlit
- pinecone
- langchain.llms.openai
- langchain.vectorstores.pinecone
- langchain.embeddings.openai
- langchain.chains.summarize
- langchain.document_loaders

You can install the required packages using pip:
```
pip install streamlit pinecone langchain
```

## Usage
1. Provide your OpenAI API key, Pinecone API key, Pinecone environment, and Pinecone index name in the sidebar.
2. Upload the source document in PDF format using the file uploader.
3. Click on the "Summarize" button to start the summarization process.

Note: Please make sure all the required fields are filled before clicking the "Summarize" button.

If the summarization process is successful, the summary will be displayed in the Streamlit app.

## Troubleshooting
If you encounter any errors during the process, an error message will be displayed with the details of the error.

Please ensure that you have provided valid API keys and other necessary information. Also, make sure the uploaded document is in PDF format.


## Disclaimer
This app is provided as-is without any warranty. The app developer and OpenAI do not take any responsibility for the accuracy or reliability of the generated summaries.

Use the app responsibly and verify the summaries for critical applications or important documents.
