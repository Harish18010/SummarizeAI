# PDF_Summarizer

PDF Summarizer with Text  Audio Output (Using Colab)

This is a simple Google Colab-based tool to help you **summarize long PDF files** using BART or DistilBART, and optionally convert those summaries into **spoken audio files** (MP3 format) using Google Text-to-Speech.

You can choose from:
-  **Brief** summaries (short and to the point)
-  **Detailed** summaries (more thorough)
 - **Bullet** summaries (for easy reading)

---

##  Features

- Upload multiple PDF files from your computer.
- Extract and clean text from the PDFs.
- Uses (`BART` or `DistilBART`) to summarize the content.
- Multi-stage summarization for very large documents.
- Save the summary as a `.txt` file.
- Optionally, generate an audio version of the summary as an `.mp3` file.

---

##  Requirements

Run this in **Google Colab**. The required libraries will be installed automatically:
- transformers 
- torch 
- gtts 
- pymupdf


