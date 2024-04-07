
# Semi-Custom Chatbot and Streamlit Integration Project 🤖💡

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-Integrated-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## Introduction 🌟

This project showcases the integration of advanced AI models for query and answer generation in a chatbot, complemented by a Streamlit application for an interactive user interface. It includes multiple Jupyter notebooks, each demonstrating a different aspect of chatbot functionality using OpenAI and GEMINI models. Additionally, the project features interaction with a PostgreSQL database, enabling the chatbot to retrieve and store information dynamically as part of the conversation flow.

## Table of Contents 📚

- Introduction
- Getting Started
- Installation
- Project Structure
- Usage
- Features
- Dependencies
- Configuration
- Streamlit Application
- Detailed Notebook Descriptions
- Documentation
- Examples
- Troubleshooting
- Contributors
- License

## Getting Started 🚀

### Installation

Ensure Python and pip are installed, then clone the repository and install the required dependencies:

```
git clone <repository-url>
cd <project-directory>
pip install -r requirements.txt
```

## Project Structure 🏗️

The project includes several Jupyter notebooks and a Streamlit application. Each notebook explores different combinations of AI models for chatbot functionality:

- **Jupyter Notebooks:**
  - `semi_custom_final_GEMINI_OpenAI.ipynb`
  - `semi_custom_final_OpenAI.ipynb`
  - `semi_custom_final_GEMINI.ipynb`
- **Streamlit Application:**
  - `semi_custom_final.py`: A web interface integrating the chatbot functionalities.

## Usage 🛠️

To run the notebooks, use Jupyter Notebook or JupyterLab. For the Streamlit application:

```
streamlit run semi_custom_final.py
```

## Features ✨

- Advanced query and answer generation using OpenAI and GEMINI models.
- Interactive user interface through Streamlit.
- Exploration of different AI model combinations for enhanced chatbot interactions.
- Integration with a PostgreSQL database for dynamic data retrieval and storage.

## Dependencies 📦

This project requires the following dependencies:
- Python 3.9 or higher
- LangChain
- Streamlit (for the Python application)
- pandas
- PostgreSQL database
- OpenAI API key
- Google API key (for Gemini API integration)

## Configuration 🔧

Set the necessary environment variables for the OpenAI API key, GEMINI API key, and database credentials.

## Streamlit Application 🌐

Details the setup and functionalities of the Streamlit application, showcasing how it interacts with the AI models to provide a dynamic user experience.

## Detailed Notebook Descriptions 📓

Each notebook within the project serves a unique purpose, demonstrating various integrations and functionalities of the chatbot:

- **`semi_custom_final_GEMINI_OpenAI.ipynb`**: Demonstrates a chatbot where query generation is powered by OpenAI, and response generation is handled by GEMINI. This notebook showcases the integration of two different AI models to leverage their strengths in specific areas of the chatbot's functionality.

- **`semi_custom_final_OpenAI.ipynb`**: Focuses on utilizing the OpenAI model for both query generation and response formulation. It highlights how a single AI platform can be used to manage the entire chatbot interaction cycle, providing insights into the capabilities and limitations of using OpenAI exclusively.

- **`semi_custom_final_GEMINI.ipynb`**: Uses the GEMINI model for both query and answer generation, exploring the potential of GEMINI in handling complete chatbot functionalities. This notebook provides a deep dive into the GEMINI model's effectiveness in understanding and responding to user queries.

## Documentation 📖

Refer to the following documentation for more information on the technologies and libraries used:
- [LangChain](https://langchain.com)
- [Streamlit](https://docs.streamlit.io)
- [Pandas](https://pandas.pydata.org/docs/)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [OpenAI](https://openai.com/api/)

## Examples 📝

Examples of usage will be provided in the respective script files, demonstrating how to interact with the database using different OpenAI and Gemini Models.

## Troubleshooting 🔍

For issues related to environment setup, API keys, or database connections, refer to the respective service's documentation. For more specific problems, consider opening an issue in the project repository.

## Contributors 👥

To contribute to this project, please fork the repository and submit a pull request.

## License 📄

This project is released under the MIT License. See the LICENSE file for more details.
