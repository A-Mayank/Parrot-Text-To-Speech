# Parrot TTS

Parrot TTS is a powerful text-to-speech (TTS) engine built upon OpenVoice, featuring voice cloning and advanced control over speech parameters such as emotion, speed, and accents. It allows for highly customizable and expressive speech synthesis, making it ideal for applications requiring natural and dynamic voice output.

## Features
- 🎭 **Emotion Control**: Choose from multiple speaking styles like `friendly`, `cheerful`, `excited`, `sad`, `angry`, `terrified`, `shouting`, and `whispering`.
- ⚡ **Speed Control**: Adjust the speaking speed using the `speed` parameter (e.g., `0.9` for a slightly slower pace).
- 🌍 **Accent Selection**: Pick from various pre-trained models:
  - `en_default_se.pth`
  - `en_style_se.pth`
  - `en-au.pth` (Australian English)
  - `en-br.pth` (Brazilian English)
  - `en-default.pth`
  - `en-india.pth` (Indian English)
  - `en-newest.pth`
  - `en-us.pth` (US English)
- 🎙 **Voice Cloning**: Leverage OpenVoice to create personalized voices from existing audio samples.

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/parrot-tts.git
cd parrot-tts

# Install dependencies
pip install -r requirements.txt
```

## Usage
```bash
streamlit run app.py
```

## Demo Video 🎥
<video width="640" height="360" controls>
  <source src="demo/demo.webm" type="video/webm">
  Your browser does not support the video tag.
</video>

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

---
🚀 **Experience natural, expressive TTS with Parrot TTS!**

