AINEWSAgentic

An AI-powered news aggregation and summarization application built with Streamlit, LangChain, and the Tavily API.

1. Overview

AINEWSAgentic automatically fetches the latest Artificial Intelligence news from global sources.

Summarizes articles using a language model (LLM) into a structured markdown format.

Supports fetching news on a daily, weekly, monthly, or yearly basis.

Saves summaries for future reference in markdown files.

2. Features

AI news retrieval from the Tavily API.

Summarization using LangChain and an LLM.

Frequency options:

Daily: Last 24 hours

Weekly: Last 7 days (rolling window)

Monthly: Last 30 days

Yearly: Last 366 days

Markdown export to the AINews/ directory.

Interactive Streamlit interface.

3. Technology Stack

Python 3.10+

Streamlit

LangChain

Tavily API

Groq API (or other LLM)

Markdown formatting
