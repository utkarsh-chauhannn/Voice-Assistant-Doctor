 Voice Assistant Doctor
Voice Assistant Doctor is an AI-powered voice assistant built to simulate a doctor's initial interaction using speech-based communication. It leverages speech-to-text, natural language processing, and text-to-speech systems to interact with users in a conversational and informative way.

🚀 Features
🎙️ Converts user voice input to text using advanced speech recognition.

🧠 Processes user queries with an AI model to simulate doctor-like responses.

🔊 Uses ElevenLabs and other TTS tools to respond in a human-like voice.

🐳 Containerized using Docker for smooth deployment and environment consistency.

💬 Integrated with Gradio for a user-friendly web interface.

📁 Project Structure Highlights
brain_of_the_doctor.py: Core logic for AI-based medical query responses.

gradio_app.py: Gradio-based frontend for interacting with the assistant.

elevenlabs_output.mp3, final.mp3: Sample audio outputs from the assistant.

Dockerfile: Docker configuration for containerizing the app.

Pipfile, Pipfile.lock: Dependency management using Pipenv.

