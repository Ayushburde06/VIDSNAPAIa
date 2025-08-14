# VidSnapAI – AI-Powered Video Processing SaaS Application

VidSnapAI is a **full-stack SaaS platform** for AI-powered video and audio processing.  
It enables users to upload media, process it with advanced AI models, and download results — all in a seamless, secure web interface.

---

## 🚀 Features
- **AI Voice Synthesis** – Integrated with [ElevenLabs AI API](https://elevenlabs.io) for real-time voice generation.
- **Media Conversion Pipelines** – Powered by [FFmpeg](https://ffmpeg.org) for high-speed video/audio conversion.
- **Responsive Web UI** – Built with HTML, CSS, and Jinja templates for smooth user interaction.
- **Secure File Handling** – Safe uploads with server-side processing.

---

## 🛠️ Tech Stack
**Backend:** Python, Flask  
**Frontend:** HTML, CSS, Jinja2  
**AI API:** ElevenLabs AI API  
**Media Processing:** FFmpeg  

---

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/Ayushburde06/VIDSNAPAI.git
cd VIDSNAPAI
2.Create a virtual environment

python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
Install dependencies

pip install -r requirements.txt


Set up environment variables
Create a .env file and add:

ELEVENLABS_API_KEY=your_api_key_here


Run the application

flask run

📂 Project Structure
VIDSNAPAI/
│-- app.py            # Main Flask app
│-- templates/        # HTML templates
│-- static/           # CSS, JS, images
│-- processing/       # Media processing scripts
│-- requirements.txt  # Dependencies
│-- README.md         # Project documentation
