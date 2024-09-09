# AI-Powered Home Automation Assistant

## Overview
This project is an AI-powered voice assistant that integrates with Home Assistant to control various smart devices in your home. It’s designed to run on a Raspberry Pi but can be developed and tested on any machine with Python support. The assistant will recognize voice commands, process them using a speech recognition library, and control your smart home devices accordingly.

## Features
- **Voice Command Recognition**: Recognizes and processes voice commands using Python's `SpeechRecognition` library.
- **Text-to-Speech**: Provides voice feedback using `pyttsx3`.
- **Home Automation Integration**: Controls smart devices via Home Assistant.
- **Extensible**: Easily add new commands and functionalities.

## Tech Stack
- **Python**: Core programming language.
- **SpeechRecognition**: Library for recognizing voice commands.
- **pyttsx3**: Text-to-speech conversion.
- **Home Assistant**: Open-source home automation platform.

## Setup and Installation

### Prerequisites
- Python 3.x
- Git
- A Raspberry Pi (optional for deployment)
- Home Assistant (for controlling smart devices)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cmac-ire/ai_home_automation_assistant.git
   cd ai_home_automation_assistant
