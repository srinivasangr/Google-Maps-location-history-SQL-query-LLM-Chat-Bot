# LlamaIndex Gmaps LLM SQL Chat Bot

This project demonstrates how to process Google Maps location history data using Python, and how to create a chatbot that can query this data using LlamaIndex and a language model.

## Prerequisites

- Python 3.9 or higher
- Jupyter Notebook
- Required Python packages (install using `pip install -r requirements.txt`)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/llamaindex_gmaps_llm_sql_chat_bot.git
    cd llamaindex_gmaps_llm_sql_chat_bot
    ```

## Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook LlamaIndex_Gmaps_LLM_SQL_Chat_bot.ipynb
    ```

2. Follow the steps in the notebook to:
    - Load and process Google Maps location history data.
    - Extract place visits and activity segments.
    - Create a vector store index using LlamaIndex.
    - Query the data using a language model.

## Notebook Overview

- **Import Libraries**: Import necessary libraries such as `os`, `pandas`, `numpy`, and `llama_index`.
- **Load JSON Data**: Load Google Maps location history data from JSON files.
- **Process Data**: Extract place visits and activity segments, and convert them into pandas DataFrames.
- **Data Analysis**: Analyze and display the processed data.
- **Create Documents**: Convert DataFrame rows into documents for indexing.
- **Create Index**: Create a vector store index using LlamaIndex.
- **Query Pipeline**: Set up a query pipeline to interact with the data using a language model.

## Example Queries

- "Where was I on September 30, 2023?"
- "What are the top five places i had visited in 2023"

## License

This project is licensed under the MIT License - see the LICENSE file for details.
