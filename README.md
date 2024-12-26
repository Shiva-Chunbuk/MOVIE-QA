# Movie Question-Answering Bot

A Python-based project utilizing advanced Natural Language Processing (NLP) and web scraping techniques to answer questions about movies. This bot employs LangChain, Selenium, FAISS, and Google Generative AI to deliver accurate and detailed information.

## Repository Structure

```
Shiva-Chunbuk
│
├── .gitattributes     # Git configuration file
├── Movie QA.ipynb     # Jupyter Notebook containing the implementation
└── README.md          # Project README file
```

## Overview

This bot builds an interactive system for answering movie-related queries by:

1. **Web Scraping:** Extracting reviews from IMDb using Selenium.
2. **Embedding Generation:** Utilizing Google Generative AI embeddings for text representation.
3. **Retrieval-Augmented Generation:** Combining Wikipedia data and user reviews with advanced retrievers (FAISS and BM25).
4. **Conversational Agents:** Providing detailed responses using LangChain.

## Key Features

- **Multi-source Data Integration:** Combines Wikipedia content and IMDb reviews.
- **Custom Retrieval Functions:** FAISS and ensemble retrievers for effective search.
- **Conversational Interface:** Answer movie-related questions with context-aware responses.
- **Efficient Web Scraping:** Uses Selenium for dynamic review extraction.

## How to Run

### Prerequisites

- Python 3.8+
- Google Cloud API Key for Generative AI
- IMDbPy
- Selenium WebDriver
- Required Python libraries listed in `requirements.txt`

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Shiva-Chunbuk/Movie-QA.git
   cd Movie-QA
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Obtain a Google API key and set it as an environment variable:
   ```bash
   export GOOGLE_API_KEY=your_api_key
   ```

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Movie\ QA.ipynb
   ```

5. Follow the instructions in the notebook to initialize and use the bot.

## Example Query

```bash
Question: I want to watch a movie with my young daughter. Should we watch Oppenheimer or Inside Out?
Response: Inside Out is a better choice for a young daughter.
```

## Contributions

Feel free to contribute to the project by submitting issues or pull requests. Your feedback and ideas are highly appreciated!

