# Facial Expression Recognition

Real-Time Facial Expression Recognition using TensorFlow.js (TFJS) and FaceAPI.js.

## Overview

This project implements a real-time facial expression recognition system leveraging TFJS and FaceAPI.js. It detects human faces in live video streams and classifies their expressions into various categories, enhancing applications in human-computer interaction and emotion analysis.

## Repository Contents

- `.vscode/`: Visual Studio Code configuration files.
- `models/`: Pre-trained models used for facial detection and expression recognition.
- `face-api.min.js`: Minified version of the FaceAPI.js library.
- `index.html`: Main HTML file serving as the application's entry point.
- `script.js`: JavaScript file containing the core logic for face detection and expression recognition.

## Requirements

- Modern web browser with JavaScript enabled.
- Internet connection to load external libraries and models.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AkshadK7/Facial-Expression-Recognition.git
   cd Facial-Expression-Recognition
   ```

2. **Serve the Application**:
   - Use a local server to serve the `index.html` file. You can use Python's built-in HTTP server:
     ```bash
     # For Python 3.x
     python -m http.server 8000
     ```
     Then, navigate to `http://localhost:8000` in your web browser.

3. **Access the Application**:
   - Ensure your device has a webcam enabled.
   - Open the served `index.html` in a modern web browser.
   - Grant the browser permission to access the webcam when prompted.

## Usage

- The application will access your webcam and display the video feed.
- Detected faces will be highlighted, and their corresponding expressions will be labeled in real-time.
- Supported expressions include happiness, sadness, anger, surprise, and more.

## Live Demo

Experience the application live at: [face-expression-recognition.netlify.app](https://face-expression-recognition.netlify.app/)

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/AkshadK7/Facial-Expression-Recognition/blob/master/LICENSE) file for details.

## Acknowledgements

Special thanks to the developers of [FaceAPI.js](https://github.com/justadudewhohacks/face-api.js) and the contributors to the TensorFlow.js community for their invaluable tools and support.
```

*Note: Ensure that your browser supports WebRTC and has permissions to access the webcam for the application to function correctly.* 
