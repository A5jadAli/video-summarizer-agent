# Video Summarizer Agent 🎥

A Streamlit-based video summarization tool powered by Google's Gemini 2.0 Flash model and built with phidata. This application allows users to upload videos and get AI-generated summaries of their content.

## Features 

- Video upload and processing
- AI-powered video content summarization
- User-friendly Streamlit interface
- Support for multiple video formats
- Real-time processing status updates

## Prerequisites 

Before running this application, make sure you have:
- Python 3.8 or higher installed
- Git installed
- A Google Cloud account with access to Gemini API

## Installation 

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/video-summarizer
cd video-summarizer
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root directory and add your Gemini API key:
```bash
GOOGLE_API_KEY=your_api_key_here
```

## Usage 💻

1. Start the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Upload your video file using the interface

4. Wait for the processing to complete

5. View your video summary!

## Limitations

- Maximum video file size: 200MB
- Supported video formats: Check Streamlit's supported formats
- Internet connection required for API calls

## Acknowledgments 

- Built with [phidata](https://github.com/phidata-public/phidata)
- Powered by Google's Gemini 2.0 Flash model
- Created using Streamlit