# SPINAKER-code-examples
## Description
This repository contains basic code examples for AI in Business course Students at Kozminski University. The examples contain easy applications of OpenAI GPT-3 models with Python.

## How to run
To run the scripts successfully user needs to have python 3 installed on their computer. Intructions for python 3 installation are available <a href="https://www.python.org/downloads/">here</a>.

Neccessary python libraries need to be installed via terminal:
<br>`pip install openai, dotenv-python`

To run the file successfuly, it is also required to create `.env` file in the same folder as the desired python script.
The `.env` file should contain the following line: `OPENAI_KEY:<your_openai_api_key>`


When python is already installed. Running the scripts is possible in Terminal with the following command:
<br>`python <route_to_file>`

## Content
- Script `01_simple_app.py` presents simple app that takes product description as the input and generates marketing campaign outline as the output.
- Script `02_simple_chat.py` presents simple chat app that can be run in terminal.
- Script `03_marketing_chat_with_feedback.py` contains a simple chat app with virtual assistant focused on generating content about marketing campaigns.
- prompts presented in `.txt` files are prompts used for zero- or one-shot learning of GPT-3.5 model in the examples.

