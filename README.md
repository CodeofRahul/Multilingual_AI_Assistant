# Multilingual AI Assistant

This project is a **Multilingual AI Assistant** built using Python, Google's Generative AI (Gemini), and Streamlit. The assistant can take voice commands, process them using Google's speech recognition, generate responses using the Gemini model, and convert the response into speech using Google Text-to-Speech (gTTS). The application is designed to be user-friendly and can be accessed via a web interface powered by Streamlit.

## Features
- **Voice Command Recognition**: The assistant listens to user commands via microphone input.
- **Multilingual Support**: The assistant can recognize and respond in multiple languages (currently set to English).
- **Text-to-Speech**: Converts the generated response into speech and provides an audio file for download.
- **Streamlit Web Interface**: A simple and interactive web interface for users to interact with the assistant.

## Technologies Used
- **Python**: The core programming language used for the project.
- **SpeechRecognition**: Library for recognizing speech from audio input.
- **gTTS (Google Text-to-Speech)**: Converts text into speech.
- **Google Generative AI (Gemini)**: Used for generating intelligent responses to user queries.
- **Streamlit**: Framework for building and deploying the web interface.
- **Logging**: For tracking and debugging the application.




# **Setup Instructions**
To create environment = `conda create -p assistant python=3.10 -y`
To check available envs = `conda env list`
To check available envs = `conda info --envs`
To activate environment = `conda activate <env_name>`
To install requirements.txt = `pip install -r requirements.txt`
To check install packages = `pip list`
To check detailed about package = `pip show package_name`
To install package = `pip install package_name`
To uninstall package = `pip uninstall package_name`
To save all packages of env to a requirements.txt file = `pip freeze > requirements.txt`

# **Streamlit command:**
- To run streamlit app = `streamlit run main.py`

# **Git commands**
To add all file = `git add .`
To add any particular file = `git add <file_name>`
To commit = `git commit -m "commit message"`
To push the code = `git push origin main`

# **Docs:**
- gTTS docs : https://gtts.readthedocs.io/en/latest/
- Generate gemini api : https://ai.google.dev/gemini-api/docs/api-key
- Streamlit docs : https://docs.streamlit.io/
