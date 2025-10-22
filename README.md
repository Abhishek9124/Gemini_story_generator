# AI Story Generator

A fun and creative web application that generates and narrates stories based on your uploaded images using AI technology.

## Features

- Upload 1-10 images to inspire your story
- Choose from different story styles:
  - Comedy
  - Thriller
  - Fairy Tale
  - Sci-Fi
  - Mystery
  - Adventure
  - Morale
- Get an AI-generated story that connects all your images
- Listen to your story with text-to-speech narration
- Stories feature Indian names, characters, and places

## Technologies Used

- Python
- Streamlit (for the web interface)
- Google Gemini AI (for story generation)
- gTTS (Google Text-to-Speech for narration)
- PIL (Python Imaging Library for image handling)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Abhishek9124/Gemini_story_generator.git
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root and add your Gemini API key:
```
GEMINI_API_KEY="your-api-key-here"
```

## How to Run

1. Open a terminal in the project directory
2. Run the Streamlit app:
```bash
streamlit run app.py
```
3. Open your web browser and go to http://localhost:8501

## How to Use

1. Upload 1-10 images using the sidebar
2. Select your preferred story style
3. Click "Generate Story and Narration"
4. Wait a few moments while the AI creates your story
5. Read your story and listen to the narration

## Project Structure

- `app.py` - Main Streamlit application
- `story_generator.py` - Core functions for story generation and narration
- `requirements.txt` - List of Python dependencies
- `.env` - Environment variables (API keys)

## Notes

- Make sure your images are in PNG, JPG, or JPEG format
- For the best experience, use clear, high-quality images
- Story generation may take a few moments depending on the number of images

## Author

Abhishek
