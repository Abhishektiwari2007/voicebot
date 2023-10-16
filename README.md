Voice Bot
Voice Bot is a Python script that allows you to interact with a voice-based virtual assistant. This virtual assistant can answer questions, provide information from Wikipedia, and even play YouTube videos using Pywhatkit.

Prerequisites
Before you run the Voice Bot, make sure you have the following installed:
Python 3
The required Python libraries: speech_recognition, pyttsx3, wikipedia, and pywhatkit.
You can install these libraries using pip:
Bash
pip install speech_recognition pyttsx3 wikipedia pywhatkit
Usage
Run the script voice_bot.py.
Wait for the "I am ready, Listening ...." prompt.
Start your command with "Siri" to activate the virtual assistant.
You can give commands like:
"What is [your query]": Retrieve information from Wikipedia.
"Who is [your query]": Retrieve information from Wikipedia.
"Play [song name]": Play the requested song on YouTube.
Example
You: "Siri, what is the capital of France?"
Voice Bot: Provides information about Paris, the capital of France.
Customization
You can customize the voice assistant's name ("Siri") and the responses within the run_voice_bot function in the script.
Contributions
Feel free to contribute to this project by opening issues or submitting pull requests. We welcome enhancements and bug fixes!
