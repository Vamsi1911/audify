# Audify

Audify is a web application that allows users to generate audio files from videos, either by uploading a video file or providing the URL of a YouTube video. The application is built using React.js for the frontend and Flask for the backend. It utilizes FFmpeg for video to audio conversion and includes user authentication and an about page.

## Features

- Video to Audio Conversion: Users can upload a video file or provide a YouTube video URL to convert it into an audio file using FFmpeg.
- Caption Display: The application supports displaying captions for the generated audio file.
- Commenting System: Users can add comments to the audio file at specific timestamps, enabling collaborative discussions.
- User Authentication: Users can create accounts, log in, and access personalized features.
- About Page: Provides information about the Audify application, its purpose, and development team details.

## Technologies Used

- Frontend: React.js
- Backend: Flask
- Audio Processing: FFmpeg for video to audio conversion

## Installation

Follow these steps to set up and run the Audify application locally:

1. Clone the repository: `git clone https://github.com/Vamsi1911/audify`
2. Navigate to the project directory: `cd audify`
3. Install the frontend dependencies: `npm install`
4. Install the backend dependencies: `pip install -r requirements.txt`
5. Start the backend server: `python app.py`
6. Start the frontend development server: `npm start`
7. Access the application in your browser at `http://localhost:3000`

Note: Additional steps might be required depending on the specific configurations and dependencies of the project.

## Usage

1. Open the Audify application in your browser.
2. Create an account or log in if you already have one.
3. Choose the desired method to provide the video source (upload a file or enter a YouTube URL).
4. Specify any additional options such as captions or comments.
5. Click the "Convert" button to initiate the audio generation process.
6. Once the audio file is generated, it can be downloaded or played within the application.
7. Captions can be displayed during audio playback, and comments can be added at specific timestamps.

## Contributing

Contributions to Audify are welcome! Here are the suggested steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3. Make the necessary changes and commit them: `git commit -m "Add your commit message"`.
4. Push your changes to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request describing your changes.
