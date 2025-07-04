## Features

- **AI-Powered Content Generation**: Extracts and summarizes content from any URL using GPTScript.
- **Custom Visuals**: Generates relevant images to match the summarized content.
- **Voiceover Integration**: Adds voiceovers for each part of the generated content.
- **Text Transcription**: Displays transcription overlayed on the video.
- **High-Quality Output**: Produces an MP4 video with synchronized assets.

## Tech Stack

### Frontend
- **React**
- **TailwindCSS** for custom styling

### Backend
- **Node.js**
- **Express**

### AI & Video Tools
- **GPTScript** for AI-generated content and images
- **FFMPEG** for video processing

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-video-generator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ai-video-generator
   ```

3. Install dependencies:
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```
   - Backend:
     ```bash
     cd backend
     npm install
     ```

4. Start the application:
   - Frontend:
     ```bash
     npm start
     ```
   - Backend:
     ```bash
     npm start
     ```

## Usage

1. Open the frontend application in your browser.
2. Enter a URL in the input field and submit.
3. The application will process the URL, generate assets, and produce a downloadable video.

## Key Functionalities

1. **URL Content Processing**:
   - Fetches and extracts content from the provided URL.
   
2. **Asset Generation**:
   - Divides content into three parts and generates summaries.
   - Creates images, voiceovers, and transcription files.

3. **Video Compilation**:
   - Uses FFMPEG to combine images, audio, and text into video segments.
   - Merges segments into a final MP4 video with a polished look.
