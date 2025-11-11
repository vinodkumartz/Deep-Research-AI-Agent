# Advanced AI Agent with Search

This project demonstrates how to build an advanced AI agent in Python using LangGraph, which can perform multi-step deep research by pulling live data from sources like Google, Bing, and Reddit. The agent leverages Bright Data for real-time web data access and is designed to be scalable and production-ready.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This AI agent is designed to:
- Perform parallel searches on Google, Bing, and Reddit.
- Analyze search results and Reddit posts.
- Retrieve and analyze comments from relevant Reddit posts.
- Synthesize all gathered data into a comprehensive final answer.

## Features

- Multi-source data integration (Google, Bing, Reddit).
- Real-time data access using Bright Data.
- Scalable architecture for handling large volumes of data.
- Structured output using LangGraph and Pydantic.
- Comprehensive analysis and synthesis of data.

## Prerequisites

Before you begin, ensure you have the following:
- Python installed on your system.
- Basic knowledge of Python and AI concepts.
- Access to OpenAI API and Bright Data API keys.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/advanced-ai-agent.git
   cd advanced-ai-agent

   BRIGHT_DATA_API_KEY=your_bright_data_api_key
OPENAI_API_KEY=your_openai_api_key


### Additional Notes

- **requirements.txt**: Ensure you have a `requirements.txt` file listing all dependencies.
- **CONTRIBUTING.md**: Create a `CONTRIBUTING.md` file if you plan to accept contributions.
- **LICENSE**: Include a `LICENSE` file with the MIT License text.

This README provides a clear structure and essential information for anyone looking to set up and use the advanced AI agent.
