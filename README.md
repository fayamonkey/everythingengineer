# CustomGPT Creator

A Streamlit web application that helps you create CustomGPTs through a guided process with specialized AI assistants.

## Features

- Interactive chat interface
- Step-by-step guidance through the CustomGPT creation process
- Integration with OpenAI's GPT-4 Turbo model
- Export results as Markdown files
- Save and manage multiple CustomGPT results
- Corporate branding and professional interface

## Setup

### Automatic Setup (Windows)
1. Make sure you have Python 3.8 or higher installed
2. Double-click `setup.bat`
3. The script will:
   - Install required dependencies
   - Create a desktop shortcut
   - Start the app for the first time

### Manual Setup
1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Make sure you have your OpenAI API key ready

## Running the App

### Using the Desktop Shortcut (Windows)
- Double-click the "CustomGPT Creator" shortcut on your desktop

### Manual Start
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Open your web browser and navigate to the URL shown in the terminal
3. Enter your OpenAI API key in the sidebar
4. Start creating your CustomGPT by describing what you want to create

## Usage

1. The app will guide you through the process of creating a CustomGPT
2. Your results will be saved in the sidebar
3. You can download results as Markdown (.md) files
4. Use "Clear Chat" to start a new conversation
5. Use "Clear Results" to remove saved results

## Requirements

- Python 3.8 or higher
- OpenAI API key
- Internet connection

## Note

Make sure to keep your OpenAI API key secure and never share it publicly. 