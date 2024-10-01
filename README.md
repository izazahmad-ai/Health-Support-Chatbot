
# Mental Health Support Chatbot

This project is a Mental Health Support Chatbot built using [Streamlit](https://streamlit.io/) and [OpenAI's GPT-3.5-turbo model](https://platform.openai.com/docs/models/gpt-3-5-turbo). The chatbot provides mental health support by engaging in conversations, offering sentiment analysis, mood tracking, and personalized coping strategies based on user input.

## Features

- **Chat Interface**: Interact with the chatbot in a simple, user-friendly chat interface.
- **Sentiment Analysis**: Analyze the sentiment of user messages, categorizing them into emotions such as "Positive", "Negative", or "Neutral".
- **Mood Tracking**: Track the user's mood over time, visually represented in charts.
- **Coping Strategies**: Offer personalized coping strategies based on the user’s emotional state.
- **Session Summaries**: Summarize the conversation and provide insights about the user's mood and interactions.
- **Helpful Resources**: Provide quick access to mental health resources for immediate help.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/izazahmad-ai/Health-Support-Chatbot.git
    cd Health-Support-Chatbot
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv env
    .\env\Scriptsctivate  # On Windows
    source env/bin/activate  # On macOS/Linux
    ```

3. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your OpenAI API key**:
    - Obtain your OpenAI API key from [OpenAI](https://platform.openai.com/account/api-keys).
    - Add your API key to the environment variable `OPENAI_API_KEY` or directly replace `'your_openai_api_key'` in the `app.py` file with your actual API key.

## Usage

1. **Run the Streamlit application**:
    ```bash
    streamlit run app.py
    ```

2. **Open the URL (typically `http://localhost:8501`) in your web browser.**

3. **Start interacting with the chatbot**:
    - Enter your message in the input field and click the "Send" button.
    - The chatbot will respond, analyze your sentiment, track your mood, and offer appropriate coping strategies.

## Project Structure

- `app.py`: The main application file containing the Streamlit code and chatbot logic.
- `requirements.txt`: Lists the required Python dependencies.

## Use Cases

### 1. **Daily Mood Tracker**
A user can interact with the chatbot daily to track their mood. The chatbot will analyze the sentiment of the user’s messages and visualize how their mood changes over time in the form of a chart. Users can use this data to understand emotional patterns and take appropriate actions to maintain their mental well-being.

### 2. **Emotional Support**
The chatbot can serve as a simple, non-intrusive tool to provide emotional support. A user who feels down or overwhelmed can communicate with the chatbot and receive personalized coping strategies based on their input sentiment. The chatbot also provides a list of professional mental health resources if further help is needed.

### 3. **Self-Reflection Tool**
A user can use the chatbot as a self-reflection tool by inputting their thoughts and feelings. The chatbot will respond with sentiment analysis and suggestions on how to cope with the emotions being experienced. Over time, users can review session summaries to better understand their emotional state and its progression.
