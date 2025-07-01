AI-Powered Video to GIF Generator
This project is a web-based tool that allows users to automatically generate captioned GIFs from video files. Users can provide a theme prompt and upload a video, and the application will extract short clips, overlay the prompt as a caption, and convert them into downloadable GIFs.

🚀 Live Demo
![{FBB3DEA5-9E40-465E-888F-72BAD1E65293}](https://github.com/user-attachments/assets/51b753a2-43d8-4f62-b4d4-9bed74878a8a)
https://ai-powered-video-to-gif-generator-sigma.vercel.app/


✨ Features
User-friendly Interface: A clean and simple UI built with Tailwind CSS.

Video Upload: Supports uploading of MP4 video files.

Prompt-based Captions: Add any text as a caption to your generated GIFs.

Automatic Clip Selection: The application intelligently selects multiple segments from the video to convert into GIFs. (Currently simulated on the frontend).

In-Browser GIF Conversion: Uses gif.js to perform all conversion work directly in the browser, with no server-side processing required.

Responsive Design: The interface is designed to work on various screen sizes.

Downloadable GIFs: Easily preview and download the generated GIFs.

🛠️ How to Use
Clone the repository:

git clone https://github.com/your-username/your-repository-name.git

Navigate to the project directory:

cd your-repository-name

Run locally:
Since this is a single HTML file with no backend dependencies, you can simply open the index.html file in your web browser. For the best experience and to avoid potential CORS issues with local files, it's recommended to use a simple local server.

If you have Python installed:

python -m http.server

Or use the Live Server extension for VS Code.

Generate GIFs:

Enter a theme or caption in the "GIF Theme Prompt" input field.

Click the "Upload Video" area to select an MP4 file from your computer.

Click the "Generate GIFs" button.

The application will process the video and display the generated GIFs below.

Click the "Download GIF" button on any of the generated images to save it.

💻 Technology Stack
HTML5: For the basic structure of the web page.

Tailwind CSS: For styling the user interface.

JavaScript: For all the client-side logic, including video processing and DOM manipulation.

gif.js: A JavaScript library for creating animated GIFs in the browser.

🔮 Future Improvements
This prototype demonstrates the core user flow. Future enhancements could include:

Backend Integration: Connect to a real backend service to:

Process YouTube URLs.

Use an AI transcription service (like OpenAI Whisper) to get a full video transcript.

Implement a language model to analyze the transcript and the user's prompt to identify the most relevant video segments for GIF creation.

Advanced Captioning: Allow for customization of caption font, size, color, and position.

Clip Selection UI: Let users manually select or adjust the video clips they want to convert.

More Output Formats: Add support for other formats like WebM or silent MP4 clips.
