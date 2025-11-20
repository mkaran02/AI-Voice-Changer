# 🎙️ Voice AI Studio — Advanced RVC Voice Changer + Hyper-Realistic TTS  
**Futuristic Neon UI • Studio-Grade Conversion • Gradio Dashboard**

This repository contains a **Google Colab–optimized Voice AI Studio**, combining:

✅ **Retrieval-Based Voice Conversion (RVC)**  
✅ **Hyper-Realistic Text-to-Speech (Murf API)**  
✅ **Futuristic Neon / Cyberpunk UI (Custom Gradio Design)**  
✅ **Pitch 1 / Pitch 12 repository auto-switching**  
✅ **Auto-model download system (HuggingFace / Google Drive)**  
✅ **Real-time logs, debugging, and audio download support**  

Use this project to create **AI voiceovers, song covers, TTS**, and experimental voice transformation workflows.

---

## 🚀 Features

### 🔊 Voice Conversion (RVC)
- High-quality RVC engine with advanced controls:
  - Pitch shifting  
  - Index rate control  
  - Filter radius  
  - RMS mix  
  - Reverb effects  
  - Volume controls (main, backup, instrument)  
  - Protect settings  
  - Algorithm selection: `rmvpe` and `mangio-crepe`

### 🗣️ Text-to-Speech (Murf API)
- Generate studio-grade TTS:
  - Supports WAV / MP3 / FLAC  
  - Sample rates: 8000, 24000, 44100, 48000  
  - MONO / STEREO  
  - 15+ multilingual voices  

### 🎛️ Futuristic Neon UI
- Advanced 3D cards  
- Cyberpunk gradients  
- Animated layouts  
- Landing page + Voice Changer + TTS + Help + About  

### 📦 Additional Features
- Auto-installation of Python 3.10  
- Auto-repo clone based on pitch selection  
- Auto-model download system (HuggingFace / Drive)  
- Auto-extraction and clean sorting  
- Google Drive integration  
- Direct download button inside UI  

---

## 📁 Project Structure
📦 Voice-AI-Studio
├── 📜 notebook_code.py (your Colab script)
├── 🎨 custom UI (CSS inside code)
├── rvc_models/ (auto-generated)
├── song_output/ (generated audio)
├── tts_output.* (generated TTS)
└── README.md


---

## 🧩 Dependencies

All dependencies auto-install inside the Colab notebook:

- Python 3.10  
- PyTorch 2.3.1 (CUDA 11.8)  
- ONNX Runtime / ORT GPU  
- librosa, numpy, scipy  
- Gradio  
- sox  
- Murf AI Python SDK  
- gdown  

---

## ▶️ How to Use (Quick Start)

### 1️⃣ Open the Colab Notebook  
Upload your notebook or open the one in this repo.

### 2️⃣ Run Step-1 → Step-7 sequentially  
Each cell includes clear instructions.

### 3️⃣ Add Murf API Key  
Find this inside **Cell 7**:

```python
MURF_API_KEY = "your_key_here"


4️⃣ Upload Model or URL

Paste HuggingFace or Drive model link:

model_url = "YOUR_MODEL_LINK"
model_name = "your_model_name"

5️⃣ Launch UI

Run Step 7 to launch the futuristic dashboard:

🔮 Voice AI Studio started!


You will get a shareable public link.

🎤 Voice Conversion Workflow

Upload an audio file (prefer .wav)

Select your downloaded RVC model

Adjust parameters

Click Convert

Download from the UI

Output stored here:
/content/FIX/song_output/*.wav

🗣️ TTS Workflow

Enter text

Select voice

Choose format + sample rate

Click Generate

Output stored here:
/content/FIX/tts_output.*

📸 Images Used in UI

Images should be placed in:

/content/image.png


You can change this path inside the code.

🌐 Supported Model Sources
✔ HuggingFace
https://huggingface.co/.../model.zip

✔ Google Drive
https://drive.google.com/file/d/<FILE_ID>/view

🛠️ Customization

You can modify:

🎨 UI CSS

Inside the notebook:

custom_css = r"""
   ...
"""

🧪 Parameters

Inside the voice conversion function:

voice_conversion()

📜 License

This repository is for educational and research purposes only.
Do not misuse voice cloning for unethical or illegal activities.

🤝 Contributing

If you'd like new skins, TTS engines, or real-time RVC support, feel free to open an issue or PR.

⭐ Support

If this project helped you, please ⭐ star the repository and share the word!


