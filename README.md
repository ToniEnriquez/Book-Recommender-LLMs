# Book-Recommender-LLMs
A Book-Recommender created using Python, OpenAI, HuggingFace Zero-Shot, LangChain and Gradio. 

Required: Open AI API key - you must add credits into your account in order for it to run.

1. Text data cleaning (code in the notebook data-exploration.ipynb)
2. Semantic (vector) search and how to build a vector database (code in the notebook vector-search.ipynb). This allows users to find the most similar books to a natural language query (e.g., "a book about a person seeking revenge").
3. Doing text classification using zero-shot classification in LLMs (code in the notebook text-classification.ipynb). This allows us to classify the books as "fiction" or "non-fiction", creating a facet that users can filter the books on.
4. Doing sentiment analysis using LLMs and extracting the emotions from text (code in the notebook sentiment-analysis.ipynb). This will allow users to sort books by their tone, such as how suspenseful, joyful or sad the books are.
5. Creating a web application using Gradio for users to get book recommendations (code in the file gradio-dashboard.py).

- kagglehub
- pandas
- matplotlib
- seaborn
- python-dotenv
- langchain-community
- langchain-opencv
- langchain-chroma
- transformers
- gradio
- notebook
- ipywidgets

(full course I followed and learnt from : Credits to fullCodeCamp for teaching such a wonderful course on LLMs!)

