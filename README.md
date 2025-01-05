# Baymax: Your Personal Healthcare Companion

Welcome to the Baymax project, an AI-powered virtual assistant inspired by Disney's Big Hero 6. This project combines hardware and software to create an interactive companion that can assist with healthcare advice, reminders, and everyday tasks.

POV JUST AN IDEATION RIGHT NOW

## Features

- **Voice Interaction:** Baymax listens and responds to user queries using speech recognition and text-to-speech.
- **Emotion Detection:** Analyzes user emotions via facial recognition.
- **Healthcare Assistance:** Provides basic healthcare tips and reminders.
- **Weather Updates:** Fetches real-time weather information.
- **Fun and Entertainment:** Tells jokes and fun facts to lighten the mood.

## Hardware Requirements

- Raspberry Pi (Model 4 recommended) or Laptop for testing.
- USB Microphone for voice input.
- Speakers or headphones for audio output.
- Webcam for emotion detection (optional).

## Setup Instructions

### Assemble Hardware:
1. Connect the USB microphone and speakers to your Raspberry Pi or laptop.
2. (Optional) Attach a webcam for emotion detection.

### Install Software:
1. Install Raspberry Pi OS or set up your laptop with Python 3.
2. Install required Python libraries.

## Software Requirements

To install the necessary dependencies, run:

```bash
pip install speechrecognition pyttsx3 requests deepface openai
