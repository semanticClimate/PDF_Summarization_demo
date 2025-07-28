# Demonstration of PDF Summarization

<a href="https://colab.research.google.com/github/semanticClimate/PDF_Summarization_demo/blob/main/RevLit_PDF_Summarization.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

DOI Zenodo badge: 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16526790.svg)](https://doi.org/10.5281/zenodo.16526790)

Citation:

Barbhuiya, S., S, A., Jawed, M., Kumari, R., Simon, W., Yadav, G., & Murray-Rust, P. (2025). Demonstration of PDF Summarization (0.1a). Zenodo. https://doi.org/10.5281/zenodo.16526790

**Description:**

This Jupyter notebook provides an end-to-end pipeline for summarizing scientific PDFs using Natural Language Processing (NLP) techniques. It extracts text from uploaded PDFs and generates concise summaries using transformer-based models.

#### Features
- Upload and parse PDF documents
- Extract meaningful text content
- Generate summaries using Hugging Face Transformers (e.g., BART, T5)
- Optionally view original and summarized text side-by-side
- Includes visualization support with PyMuPDF and IPython.display
#### Requirements
1. Install the following packages:
2. pip install transformers
3. pip install PyPDF2
4. pip install fitz
5. pip install PyMuPDF
6. pip install nltk
7. pip install torch

#### How to Use
1.	Clone this repository or download the notebook.
2.	Launch Jupyter Notebook or Google Colab.
3.	Upload your scientific or research-based PDF.
4.	Run all cells to:
        - Extract the full text
        - Preprocess and chunk the content
        - Generate a summary using a transformer model

#### Structure
- upload_pdf() – Upload and read PDF files
- extract_text() – Extract text from all pages
- summarize_text() – Use pre-trained summarization models
- visualize() – Display original vs. summarized content
  
#### Applications
- Research paper summarization
- Literature review automation
- Information extraction for large documents
 
 
#### Notes
- Pretrained models like facebook/bart-large-cnn or t5-base are used.
- Results depend on PDF formatting quality.

Reviewers & review process: \<Add reviewers and review process link\> 

---

Software citation information: [CITATION.cff](CITATION.cff)

License: Apache License Version 2.0, January 2004 http://www.apache.org/licenses/ | License information: [LICENSE](LICENSE)
