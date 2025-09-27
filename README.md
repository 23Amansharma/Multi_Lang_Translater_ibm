# Multi_Lang_Translater_ibm
🌍 Multi Language Translator with Hinglish Support, History & TTS

A powerful and user-friendly language translator built using Transformers, Gradio, gTTS, and Indic Transliteration.
This app can auto-detect languages, supports Hinglish to Hindi transliteration, generates confidence scores, maintains translation history, and provides text-to-speech pronunciation for translated text.

<!-- You can replace this with an actual screenshot -->

🚀 Features

✅ Translate between 12+ languages
✅ Auto language detection
✅ Hinglish to Devanagari transliteration
✅ Text-to-speech (TTS) pronunciation using gTTS
✅ Translation history tracking
✅ Confidence score indicator
✅ Language swap functionality
✅ Clean, modern Gradio UI with custom CSS

🌐 Supported Languages
Language	Code
English	en
Hindi	hi
Marathi	mr
Gujarati	gu
Tamil	ta
Malayalam	ml
French	fr
German	de
Spanish	es
Chinese	zh
Japanese	ja
Korean	ko
🛠️ Installation
git clone https://github.com/yourusername/multilang-translator.git
cd multilang-translator
pip install -r requirements.txt

Or install manually:
pip install transformers sentencepiece gradio langdetect indic-transliteration gtts

▶️ Run the App
python app.py


Or from a notebook:

!python app.py


After launch, Gradio will give you a link like:
http://127.0.0.1:7860 or a shareable public link.

📁 Project Structure
multilang-translator/
├── app.py                # Main application file
├── README.md             # This file
├── requirements.txt      # Dependencies
└── assets/               # Screenshots, logos (optional)

✨ UI Highlights

🔄 Real-time translation (optional toggle)

🗣️ Hinglish Transliteration — Convert "kya haal hai" → "क्या हाल है"

🎧 Pronunciation — Hear the translated text via Google TTS

📜 Recent Translation History — Tracks your last 10 translations

🔁 Language Swap — Quickly switch between source and target
