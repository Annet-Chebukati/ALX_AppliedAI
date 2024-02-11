# Forget Skimming, Ask Away - Chatting with Documents

Welcome to the future of document interaction, powered by Language Model Chatbots. It's time to bid farewell to the tedious task of skimming and embrace a more efficient way of extracting information.

In the ever-evolving world of document interaction, traditional methods often fall short, leading to inefficiency and delayed information retrieval. Imagine the countless hours you've spent navigating through extensive documents, hunting for that one piece of elusive information. Well, those days are behind us.

## Hands-On with PrivateGPT

Below is a step-by-step guide on how I set up and used PrivateGPT.

## Prerequisites

Before getting started, make sure you have Git, Python, and Conda installed on your machine.

## Installation and Setup

1. **Clone the PrivateGPT repository**

    I cloned the PrivateGPT repository using the following command:

    ```
    git clone https://github.com/imartinez/privateGPT
    ```

2. **Change your directory to privateGPT**

    I navigated into the cloned repository:

    ```
    cd privateGPT
    ```

3. **Create and Activate a virtual environment**

    I created a new virtual environment using Conda and activated it:

    ```
    conda create --name privategpt python=3.11
    conda activate privategpt
    ```

4. **Install poetry**

    I installed poetry, a tool for dependency management in Python:

    ```
    pip install poetry
    ```

5. **Install dependencies**

    I installed the necessary dependencies:

    ```
    poetry install --with ui,local
    ```

6. **Run PrivateGPT setup**

    I ran the PrivateGPT setup script to download all the required models and files. This took a while as it downloaded large files:

    ```
    poetry run python scripts/setup
    ```

7. **Run PrivateGPT**

    Finally, I ran PrivateGPT:

    ```
    poetry run python -m private_gpt
    ```

    Then, I navigated to http://0.0.0.0:8001 in my web browser.

## Modes of Operation

PrivateGPT offers three modes of operation:

- **Query Docs**: This mode uses the context provided by the file you uploaded and answers questions posted in the chat.
- **Search in Docs**: This is a fast search that returns the 4 most related texts with their source document and page.
- **LLM Chat**: This is a non-contextual chat with the LLM. The file will not be sent as a context to the LLM.

## Next Steps

The next step is to upload your files and start chatting. You can do so using the "Upload File(s)" button and then selecting the "Query Docs" option.

![Private GPT](https://github.com/Annet-Chebukati/ALX_AppliedAI/blob/master/Chatting_With_Documents/Private%20GPT.png)

