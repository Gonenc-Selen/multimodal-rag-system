Multimodal RAG System

A Python-based Multimodal Retrieval-Augmented Generation (RAG) pipeline that:

-  Extracts text and images from PDFs
-  Creates embeddings for text (Sentence-Transformers) and images (CLIP)
-  Indexes embeddings with FAISS for similarity search
-  Generates natural-language answers using a text2text-generation model (Google Flan-T5)
-  Exposes a Gradio web interface for uploading PDFs and querying both text & image contexts

Repository Structure
- multimodal_rag.py       # Main RAG pipeline and Gradio app in one script
- requirements.txt        # Python package dependencies
- README.md               # Project overview and usage instructions
