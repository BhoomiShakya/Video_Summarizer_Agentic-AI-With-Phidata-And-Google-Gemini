# Multimodal AI Agent - Video Summarizer

## Overview
The **Multimodal AI Agent - Video Summarizer** is a Streamlit-based web application that leverages the power of Gemmini 2.0 Flash Exp and Google Generative AI to analyze uploaded video files. It provides actionable insights by answering user queries about the video content using advanced AI and supplementary web research.

## Features
- **Video Upload:** Supports video files in `.mp4`, `.mov`, and `.avi` formats.
- **AI-Powered Analysis:** Utilizes the Gemmini 2.0 Flash Exp model and DuckDuckGo search for enhanced contextual understanding.
- **Interactive User Queries:** Accepts user-defined questions or insights to tailor the analysis.
- **Real-Time Video Playback:** Displays the uploaded video for easy reference.
- **User-Friendly Interface:** Built using Streamlit for an intuitive user experience.

## Installation

### Prerequisites
- Python 3.8+
- A Google Generative AI API Key

### Setup
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory and add your Google API key:
   ```env
   GOOGLE_API_KEY=your_api_key_here
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the application in your browser.
2. Upload a video file in one of the supported formats.
3. Provide specific questions or insights in the text area.
4. Click the **Analyze Video** button to start the analysis.
5. View the AI-generated insights under the **Analysis Result** section.

## Code Structure
- `app.py`: Main application file containing Streamlit logic.
- `.env`: Environment variables file for API keys.
- `requirements.txt`: List of required Python packages.

## Dependencies
- **Streamlit**: For building the web application.
- **Google Generative AI**: For video processing and AI analysis.
- **Phidata**: For AI agent and tool integration.
- **dotenv**: For managing environment variables.
- **time**: For handling processing delays.
- **pathlib**: For file operations.

## Acknowledgments
- [Streamlit](https://streamlit.io/) for the interactive UI.
- [Google Generative AI](https://cloud.google.com/generative-ai) for powerful AI capabilities.
- [Phidata](https://phidata.com/) for enabling multimodal agent integration.

