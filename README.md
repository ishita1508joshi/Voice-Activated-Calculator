# Voice-Activated Calculator

A simple Python-based voice-activated calculator that listens to your voice commands, processes mathematical expressions, and speaks the results back to you.

## Features

- **Voice Command Recognition**: Uses speech recognition to listen to user input.
- **Mathematical Evaluation**: Evaluates basic mathematical expressions such as addition, subtraction, multiplication, and division.
- **Text-to-Speech**: The result is spoken back to the user using text-to-speech technology.
- **Exit Functionality**: Simply say "exit" to terminate the program.

## Requirements

Before running the program, make sure you have the following libraries installed:

- `speechrecognition`: For converting speech to text.
- `pyttsx3`: For converting text to speech.
- `pyaudio`: For microphone access (required for `speechrecognition`).

You can install them using `pip`:

```bash
pip install speechrecognition pyttsx3 pyaudio
