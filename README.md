# news-summarizer


## Goal for this project
A web application to aggregate and summarize relevant news articles into key points using Large Language Model (LLM) and Retrieval-Augmented-Generation (RAG) based on user query. The purpose of this project is that news articles can be lengthy and different news sources can release similar news articles. Thus, retrieved relevant articles based on the user's query will be grouped together and summarized into key points to give a straight answer to the user, reducing the need to read multiple news articles. 

The news articles are to be retrieved from https://newscatcherapi.com. Users should be allowed to filter the news articles in a number of ways e.g. date, sources, and language, to give more accurate results as there is a limited context window for LLMs.

### Stretch Goal
- [ ] Deduplication of identical news articles
- [ ] Semantic splitting of news articles to chunks

## Technology Stack
- Streamlit for application
- LLM (TBC)
- News articles as data

