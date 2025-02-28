# Building-a-Support-Agent-Chatbot-for-CDP-How-to-Questions
# CDP Support Agent Chatbot

A simple Python-based chatbot designed to answer questions regarding Customer Data Platforms (CDPs) by scraping documentation from various CDP solutions. The chatbot utilizes natural language processing and fuzzy string matching to deliver relevant responses.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Scrapes documentation from multiple CDP providers: Segment, mParticle, Lytics, and Zeotap.
- Processes user queries and returns relevant answers based on scraped content.
- Handles irrelevant questions gracefully.
- Provides a user-friendly GUI using Tkinter.

## Technologies Used

- Python
- Requests (for web scraping)
- Beautiful Soup (for parsing HTML)
- NLTK (Natural Language Toolkit for text processing)
- FuzzyWuzzy (for fuzzy string matching)
- Tkinter (for GUI)

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/cdp-support-agent-chatbot.git
