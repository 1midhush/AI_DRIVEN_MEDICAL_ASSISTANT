# Llama2 Medical Bot
## Video Guide

For a quick walkthrough, watch this video:  
[![Watch the video](https://img.youtube.com/vi/bRvQjwyw_TY/0.jpg)](https://www.youtube.com/watch?v=bRvQjwyw_TY)

---

The Llama2 Medical Bot is a cutting-edge tool designed to provide accurate medical information by answering user queries. Leveraging state-of-the-art language models and vector stores, this bot offers reliable and context-aware responses. This README will guide you through the setup and usage of the Llama2 Medical Bot.

---

## Table of Contents

- [Introduction](#llama2-medical-bot)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Prerequisites

Ensure the following prerequisites are installed before using the Llama2 Medical Bot:

- **Python 3.6 or higher**
- Required Python packages (installable via `pip`):
    - `langchain`
    - `chainlit`
    - `sentence-transformers`
    - `faiss`
    - `PyPDF2` (for PDF document loading)

---

## Installation

1. **Clone the repository**:  
    ```bash
    git clone https://github.com/your-username/langchain-medical-bot.git
    cd langchain-medical-bot
    ```

2. **Create a virtual environment** (optional but recommended):  
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the required Python packages**:  
    ```bash
    pip install -r requirements.txt
    ```

4. **Download language models and data**:  
   Follow the instructions in the Langchain documentation to download and configure the necessary language model and vector store.

5. **Configure the project**:  
   Update the `DB_FAISS_PATH` variable and other necessary configurations in the code.

---

## Getting Started

1. **Set up your environment** and install the required packages as described in the [Installation](#installation) section.  
2. **Prepare language models and data** using the Langchain documentation.  
3. **Run the bot** using the provided Python script or by integrating it into your application.  

---

## Usage

To use the Llama2 Medical Bot:  

1. **Start the bot**: Run your application or the provided Python script.  
2. **Ask a query**: Send medical-related queries to the bot via the interface.  
3. **Get a response**: The bot provides a detailed, context-aware answer, along with references when applicable.  
4. **Customize as needed**: You can modify the bot to focus on specific topics or query types based on your requirements.

---


## Contributing

Contributions to the Llama2 Medical Bot are welcome! Follow these steps to contribute:  

1. Fork the repository to your GitHub account.  
2. Create a new branch for your feature or bug fix.  
3. Make your changes and test them thoroughly.  
4. Submit a pull request with a detailed explanation of your changes.  

---

## License

This project is licensed under the MIT License.

---
