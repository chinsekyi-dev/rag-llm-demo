# RAG LLM Demo

A Retrieval-Augmented Generation (RAG) system built with LangChain, ChromaDB, and Google Gemini for intelligent document querying.

## Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd rag-llm-demo
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the project root:
   ```env
   GOOGLE_GENAI_API_KEY=your_gemini_api_key_here
   ```

5. **Add your PDF documents**
   Place PDF files in the `data/pdf/` directory

## Usage

Open the Jupyter notebook:
```bash
jupyter notebook notebooks/document.ipynb
```