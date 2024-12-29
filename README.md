# RasaChatbot_English

RasaChatbot_English is a chatbot built using Rasa, an open-source conversational AI platform. This chatbot is designed to assist with providing information related to 11 different crops. It leverages natural language understanding (NLU) and machine learning to understand user queries and respond with relevant agricultural data.

## Features

- **Crop Information**: Provides detailed information about 11 different crops for now.
- **Custom Actions**: Performs specific actions based on user input.
- **Easy Integration**: Configured to connect to external services using Rasa's credentials and endpoints.
- **Test Coverage**: Includes test scripts to validate the chatbot’s functionality.
  
## Project Structure

The project is organized as follows:

- `.rasa/cache/`: Contains cached files for the Rasa chatbot.
- `actions/`: Custom actions used by the chatbot.
- `data/`: Contains data related to 11 crops.
- `models/`: Machine learning models used by the chatbot.
- `tests/`: Contains test files to verify the chatbot's functionality.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `config.yml`: Rasa configuration file for the project.
- `credentials.yml`: Stores credentials required for the chatbot to connect to external services.
- `domain.yml`: Defines the domain of the chatbot, including intents, entities, and responses.
- `endpoints.yml`: Contains endpoint configurations for external services.
- `story_graph.dot`: Defines the stories of the chatbot, outlining possible conversational paths.

## Installation

To run this chatbot, ensure that you have Rasa installed. You can install Rasa with pip:

```bash
pip install rasa
```
## Steps to Run the Chatbot:
1. Clone this repository:

```bash
git clone https://github.com/ayfyan/RasaChatbot_English.git
cd RasaChatbot_English
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Train the model:
```bash
rasa train
```
4. Run the chatbot:
```bash
rasa shell
```

## Testing
The tests/ folder contains various test scripts to validate the chatbot's functionality and ensure everything works as expected.

