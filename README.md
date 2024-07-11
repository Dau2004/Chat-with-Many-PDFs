

---

# Chat with Multiple PDFs :books:

![App Screenshot](screenshot.png![Screenshot 2024-07-11 015926](https://github.com/Dau2004/Chat-with-Many-PDFs/assets/144565388/74ef63b8-d25f-441a-a662-47147e4ca41a)
)

## Introduction

Welcome to the **Chat with Multiple PDFs** application! This app allows you to upload multiple PDF documents, process them, and interactively ask questions based on the content of those documents. It's powered by advanced language models and vector search to provide accurate and relevant responses.

## Features

- **Upload Multiple PDFs**: Easily upload multiple PDF files from your device.
- **Text Extraction**: Automatically extract text from all uploaded PDFs.
- **Text Chunking**: Split extracted text into manageable chunks for better processing.
- **Vector Search**: Utilize FAISS (Facebook AI Similarity Search) for efficient text retrieval.
- **Conversational AI**: Interact with your documents using a conversational interface powered by Hugging Face language models.
- **Memory Integration**: Maintain context and chat history for a coherent conversation flow.

## Installation

To get started with the app, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Dau2004/chat-with-multiple-pdfs.git
   cd chat-with-multiple-pdfs
   ```

2. **Install Dependencies**
   Make sure you have [conda](https://docs.conda.io/en/latest/miniconda.html) installed. Then, create a new environment and install the required packages:
   ```bash
   conda create -n pdf-chat python=3.9
   conda activate pdf-chat
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add your Hugging Face API token:
   ```plaintext
   HUGGINGFACEHUB_API_TOKEN=your_hugging_face_api_token
   ```

4. **Run the Application**
   Start the Streamlit app by running:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Upload PDFs**: Use the sidebar to upload one or more PDF files.
2. **Process Documents**: Click the "Process" button to extract and analyze text from the uploaded PDFs.
3. **Ask Questions**: Enter your question in the text input field at the top of the main page and receive responses based on the content of your documents.

## Technologies Used

- **Streamlit**: Web framework for creating interactive web applications.
- **PyPDF2**: Library for reading PDF files.
- **LangChain**: Framework for developing applications with large language models.
- **FAISS**: Library for efficient similarity search and clustering of dense vectors.
- **Hugging Face**: State-of-the-art machine learning models.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit Your Changes**
   ```bash
   git commit -m "Add some feature"
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature-branch
   ```
5. **Open a Pull Request**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- Thanks to the developers of Streamlit, PyPDF2, FAISS, LangChain, and Hugging Face for their amazing tools.
- Special thanks to [Chol Daniel Deng](https://github.com/Dau2004) for developing this application.

---

