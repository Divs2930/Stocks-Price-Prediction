# Stock-GPT Chatbot App with Stock Price Prediction ⚡

## 🤔 What is this?

This is an experimental Streamlit chatbot app using OpenAI api. It uses LSTM model for Stock price predection

Live demo: [Stock-GPT](https://stocks-price-prediction-jfaacacqmlvghlph5nwrum.streamlit.app/#stock-price-predection-app)

For the OpenAI license agreement, please check the Meta Platforms, Inc official license documentation on their website. 
[More info.](https://openai.com/blog/openai-api)

<img alt="demo" src="Screenshot.png">

## Features

- Chat history is maintained for each session (if you refresh, chat history clears)
- Includes "User:" and "Assistant:" prompts for the chat conversation.
- Each model (7B, 13B & 70B) runs on Replicate.
- Docker image included

## Installation

- Clone the repository
- [Optional] Create a virtual python environment with the command `python -m venv .venv` and activate it with `source .venv/bin/activate`
- Install dependencies with `pip install -r requirements.txt`
- Create an account on [Replicate](https://replicate.com/)
- [Replicate API token](https://replicate.com/account) as `REPLICATE_API_TOKEN`
- For your convenience, we include common model endpoints already in the `.env_template` file
- Run the app with `streamlit run Stock_Predictor.py`


## Usage

- Start the chatbot by selecting an API endpoint from the sidebar.
- Type your question in the input field at the bottom of the app and press enter.

## Contributing

This project is under development. Contributions are welcome!

## Acknowledgements

- Special thanks to the team at OpenAI, Replicate, a16z-infra and the entire open-source community.

## Disclaimer

This is an experimental version of the app. Use at your own risk. While the app has been tested, the authors hold no liability for any kind of losses arising out of using this application. 

## UI Configuration

The app has been styled and configured for a cleaner look. Main menu and footer visibility have been hidden. Feel free to modify this to your custom application.

## Resources

- [Streamlit Cheat Sheet](https://docs.streamlit.io/library/cheatsheet)
