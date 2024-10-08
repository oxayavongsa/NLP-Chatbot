# Context-Aware Movie Chatbot: Multi-Turn Conversations with Sentiment-Driven Responses

[![Project Status: Active](https://img.shields.io/badge/Project%20Status-Active-green.svg)](https://github.com/oxayavongsa/NLP-Chatbot)
[![GitHub issues](https://img.shields.io/github/issues/oxayavongsa/NLP-Chatbot.svg)](https://github.com/oxayavongsa/NLP-Chatbot/issues)
[![GitHub stars](https://img.shields.io/github/stars/oxayavongsa/NLP-Chatbot.svg)](https://github.com/oxayavongsa/NLP-Chatbot/stargazers)
[![GitHub license](https://img.shields.io/github/license/oxayavongsa/NLP-Chatbot.svg)](https://github.com/oxayavongsa/NLP-Chatbot/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.10-blue.svg)](https://python.org)

## Project Overview
This project is part of the AAI-520: Natural Language Processing course in the **Applied Artificial Intelligence Program** at the University of San Diego under the guidance of **Professor Kahila Mokhtari, Ph.D.** Our goal is to design and implement a **generative-based chatbot** that not only engages in multi-turn conversations but also incorporates **sentiment analysis** to adapt its responses based on the emotional tone of user input.

The chatbot is trained using the **Cornell Movie Dialogs Corpus**, enabling it to handle diverse conversations with coherence, context-awareness, and emotional sensitivity.

[Visit the Cornell Movie-Dialogs Corpus](https://www.kaggle.com/datasets/rajathmc/cornell-moviedialog-corpus)

# Repository Structure (edit when project complete)

| File/Folder Name | Description |
| ---------------- | ----------- |
| `NLP_Chatbot.ipynb` | The Jupyter Notebook containing the entire codebase for the chatbot project. |
| `NLP_Chatbot.pdf` | A PDF version of the Jupyter Notebook for easy sharing and reviewing. |
| `NLP_Chatbot.py` | A Python script version of the Jupyter Notebook for running the code outside of a notebook environment. |
| `data/` | Contains the raw dataset used in the project, including the Cornell Movie-Dialog Corpus. |
| `README.md` | This document, describing the project and repository structure. |
| `requirements.txt` | Lists all the dependencies and libraries required to run the project. |
| `LICENSE` | The licensing information for the project. |
| `.gitignore` | Specifies files and directories that should be ignored by Git. |
| `models-diagrams/` | Contains any diagrams or visual representations of the model architecture. |
| `trained_models/` | Contains pre-trained or trained model weights. |

## Project Status: 🚀 Active

## Team Members:
- **Outhai Xayavongsa** - Team Leader [![GitHub](https://img.shields.io/badge/GitHub-oxayavongsa-lightgrey)](https://github.com/oxayavongsa)
- **Saad Saeed** - Lead Assistant [![GitHub](https://img.shields.io/badge/GitHub-SaadaSaeed86-lightgrey)](https://github.com/SaadaSaeed86)
- **Anand Fernandes** - Team Member [![GitHub](https://img.shields.io/badge/GitHub-af0808-lightgrey)](https://github.com/af0808)

## Installation

To install and run the project on your machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/oxayavongsa/NLP-Chatbot.git
   cd NLP-Chatbot
2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv chatbot-env
   source chatbot-env/bin/activate

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt

4. **Download the Cornell Movie-Dialog Corpus**
   <br><i>(optional if downloading from Kaggle intead of your local drive)</i>:
   ```bash
   kaggle datasets download -d rajathmc/cornell-moviedialog-corpus
   unzip cornell-moviedialog-corpus.zip

5. (web interface here?)

### Run the Chatbot:
* Open Chatbot.ipynb in Jupyter Notebook or Colab to run the chatbot interactively.
* Or, use the command line interface to interact with the chatbot.

## Dataset Information
* We used the Cornell Movie-Dialogs Corpus which contains:

* 220,579 conversational exchanges between 10,292 pairs of movie characters.
* 9,035 characters from 617 movies.
* In total, 304,713 utterances with metadata such as genres, release year, IMDB rating, and character gender.

## Methods Used
* Natural Language Processing (NLP)
* Deep Learning using Transformer-based models
* Sentiment Analysis for emotionally aware responses

## Methodology Used (complete when done)

## Technologies
* Python for development.
* TensorFlow / PyTorch for model training.
* Hugging Face Transformers for leveraging pre-trained models like GPT.
* Jupyter Notebook or Google Colab for experimentation and testing.

## How the Chatbot Works
The chatbot leverages a Transformer-based architecture to generate responses. It maintains multi-turn conversations, adjusts based on the context, and incorporates sentiment analysis to reflect the emotional tone of the user's input. It was trained on the Cornell Movie-Dialogs Corpus, allowing it to mimic conversational flows and adapt to different styles of dialogues.

### Example Usage
(Replace the above link with an actual gif demo or video)

## Future Improvements
* Enhancing context retention over longer conversations.
* Fine-tuning the model for specific conversational tones or styles.
* Improving the user interface for web or mobile platforms.

## License
This project is licensed under the MIT License – see the LICENSE file for details.

## Acknowledgements
* Thanks to Cristian Danescu-Niculescu-Mizil and Lillian Lee for providing the Cornell Movie-Dialogs Corpus.
* Special thanks to Professor Kahila Mokhtari, Ph.D., for guidance throughout the course.
* Collaboration tools: GitHub, Slack, and Jupyter Notebook/Google Colab.
