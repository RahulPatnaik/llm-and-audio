AI Assistant with Audio Processing and Directions Module

This project consists of multiple Python modules that work together to create an AI assistant capable of audio processing and fetching directions between two locations using the Mapbox API.

###1. audio_processing.py
This module handles audio processing tasks such as recording audio, transcribing speech using a speech recognition model, generating responses using a language model, and playing audio output.

Dependencies:
NumPy (numpy)
Whisper (speech recognition library)
SoundDevice (sounddevice)
Rich (for console formatting)
LangChain (for language model and conversation chain)
TTS (Text to Speech service)
Usage:
Import the necessary modules and classes.
Initialize objects for console output, speech recognition, language model, and Text to Speech service.
Define functions for recording audio, transcribing, generating responses, and playing audio.
Use these functions within an AI assistant program to interact with users through audio input and output.

###2. directions.py
This module provides functions to fetch directions between two locations using the Mapbox Directions API. It includes functionality to calculate distance, cardinal directions, angles, and create navigation instructions.

Dependencies:
Requests (requests)
Math library (built-in)
Usage:
Import the necessary modules and functions.
Replace the placeholder Mapbox access token with your actual access token.
Use the geocode_place function to convert place names to coordinates.
Construct the API URL for fetching directions between two coordinates.
Fetch directions data from the API and process it to generate navigation instructions and calculate distances.
Print the navigation instructions and total distance for the route.

###3. main.py
This module integrates the functionality of both audio_processing.py and directions.py to create an AI assistant that can handle audio input, process it, and fetch directions based on user queries.

Usage:
Import the necessary modules and functions from audio_processing.py and directions.py.
Initialize objects and configurations for the AI assistant, including language models, prompts, and API access tokens.
Use the defined functions to handle user interactions, such as recording audio, transcribing speech, generating responses, and fetching directions.
Run the main program to start the AI assistant, which prompts users to input commands, records audio, processes it, and provides responses or directions accordingly.
Contributing
Contributions to improve or extend the functionality of these modules are welcome. Fork the repository, make your changes, and submit a pull request.

This README provides an overview of the functionality of each module and how they work together to create an AI assistant capable of audio processing and fetching directions.
