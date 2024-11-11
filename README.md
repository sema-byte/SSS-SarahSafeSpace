# Safe Space Assistant Setup Instructions

## Prerequisites
1. **Google Colab Account**: Ensure you have access to Google Colab.
2. **Gemini API Key**: Obtain a Gemini API key from Google. Follow these steps:
   - Go to https://ai.google.dev/gemini-api/docs/api-key to create and access your API key.
test

## Instructions
1. **Upload the Document**:
   - Open Google Colab and upload your PDF document with the filename `RAG.pdf`.
   
2. **Set Up the API Key**:
   - In the Colab environment, set up your Gemini API key by adding it to the environment variables:
     ```python
     import os
     os.environ["GOOGLE_API_KEY"] = "your_google_api_key_here"
     ```

3. **Run the Code**:
   - Run all the cells in the Colab notebook provided. 

4. **Access the Gradio Interface**:
   - After running all the cells, a link to the Gradio interface will be generated. Click this link to access and interact with the assistant.

## Notes
- Ensure that the document is named `RAG.pdf` when uploading.
- The Gradio interface will open in a new tab or window, where you can begin interacting with the assistant.
