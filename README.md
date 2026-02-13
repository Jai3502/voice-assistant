# Skeleton – Python Voice Assistant  

A smart and interactive **Python Voice Assistant** that listens, speaks, and performs multiple tasks for you using **speech recognition** and **text-to-speech** technology. Skeleton Jai can search Wikipedia, tell jokes, play music, open websites, and much more — all through your voice commands.

---

## Features

-  **Voice Commands:** Interact naturally using your voice.  
-  **Wikipedia Search:** Get instant 2-sentence summaries.  
-  **Jokes & Fun Facts:** Listen to random jokes and interesting facts.  
-  **Motivational Quotes:** Get inspired with random motivational quotes.  
-  **Website Access:** Open YouTube, Google, WhatsApp, GitHub, etc.  
-  **Play Songs:** Enjoy random Bollywood songs from YouTube.  
-  **Time Updates:** Ask for the current time.  
-  **Fun Actions:** Flip a coin or roll a dice for fun.  
-  **Personalized Greeting:** Greets you based on the time of day.

---

## Technologies Used

- **Python 3**
- [`pyttsx3`](https://pypi.org/project/pyttsx3/) – Text-to-Speech conversion  
- [`speech_recognition`](https://pypi.org/project/SpeechRecognition/) – Speech to text  
- [`wikipedia`](https://pypi.org/project/wikipedia/) – Wikipedia API  
- [`webbrowser`](https://docs.python.org/3/library/webbrowser.html) – To open websites  
- `datetime`, `os`, `random`, `time`

---

## Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/voice-assistant.git
   cd voice-assistant
   

2 **Create a virtual environment (optional but recommended)**

    python -m venv venv
    venv\Scripts\activate   # On Windows

3 **Install dependencies**
    
    pip install pyttsx3 SpeechRecognition wikipedia

4 **Run the assistant**
    
    python main.py


