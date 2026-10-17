# Sarcastic Gym Trainer AI 💪🤖

An interactive AI chatbot built with Python and Ollama that acts as a hilariously sarcastic gym trainer. It mocks workout excuses, calls out diet cheating, and motivates users to get back on track with funny responses and mini fitness challenges.

## Features

- Sarcastic and humorous gym trainer personality.
- Funny responses to skipped workouts and diet excuses.
- Motivational mini challenges in every response.
- Short responses of 2–3 sentences.
- Maintains conversation history during the session.
- Powered by the Qwen3.5 0.8B language model.
- Runs locally using Ollama.
- Simple command-line interface.

## Technologies Used

- Python
- Ollama
- Qwen3.5 0.8B AI Model

## Requirements

- Python 3.10 or later recommended.
- Ollama installed on your computer.
- Qwen3.5 0.8B model downloaded.
- Python Ollama library.

## Installation and Setup

### 1. Install Python

Download Python from:

https://www.python.org/downloads/

### 2. Install Ollama

Download Ollama from:

https://ollama.com/download

### 3. Download the AI Model

Open your terminal and run:

```bash
ollama pull qwen3.5:0.8b
```

### 4. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Move into the project directory:

```bash
cd Sarcastic-Gym-Trainer-AI
```

Replace the repository URL with your actual GitHub repository URL.

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Chatbot

Make sure Ollama is running, then execute:

```bash
python chatbot.py
```

Replace `chatbot.py` with your actual Python filename if necessary.

## Example Interaction

**You:** I skipped the gym today because I was tired.

**AI:** Oh, brilliant! Your muscles were waiting for a workout, and you gave them a cancellation notice. 20 squats. Now.

**You:** I cheated on my diet and ate pizza.

**AI:** One pizza and suddenly your diet has entered witness protection! Drink some water and get back to your plan. 10 push-ups. Now.

*Note: Example responses are illustrative. Actual responses depend on the model.*

## How It Works

The chatbot connects to the local Ollama server and sends user messages to the Qwen3.5 0.8B model. A system prompt defines the sarcastic gym trainer personality and response style. The program stores conversation messages so the model can use previous interactions as context.

The response temperature is set to 2, which encourages varied outputs but can also make responses less predictable.

## Project Structure

```text
Sarcastic-Gym-Trainer-AI/
├── chatbot.py
├── requirements.txt
└── README.md
```

## Future Improvements

- Add a graphical user interface.
- Track daily workout consistency.
- Introduce personalized fitness challenges.
- Add configurable sarcasm levels.
- Save conversation history between sessions.

## Disclaimer

This chatbot is intended for entertainment and general motivation. Its fitness challenges are illustrative and should be adapted to individual abilities and safety needs.

## License

Add an appropriate open-source license if you intend to permit reuse and redistribution.

## Author

Developed as a Python and local AI chatbot project.
