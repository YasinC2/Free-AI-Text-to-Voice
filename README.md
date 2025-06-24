# 🌍🎙️ Multilingual Text-to-Speech Web App

This is a lightweight, multilingual web app that converts input text into high-quality speech using the [Pollinations TTS API](https://pollinations.ai).

Supports **multiple languages** with natural-sounding voices powered by OpenAI's TTS models (via Pollinations) — now with dynamic tone and emotion control. 


## ✨ Features

- 🌐 **Multilingual support** – Enter text in English, Persian, French, Spanish, etc.
- 🔊 **Voice selection** – Choose from Alloy, Echo, Fable, Nova, Onyx, and Shimmer
- 🎧 **Voice previews** – Test voice samples with a single click
- 📥 **Audio download** – Save output as an MP3 file
- 📱 **Responsive design** – Mobile-friendly UI using Tailwind CSS
- ⚙️ **No backend needed** – Runs fully in the browser


## 🗣️ Supported Voices

* `Alloy`
* `Echo`
* `Fable`
* `Nova`
* `Onyx`
* `Shimmer`

Each voice supports multiple languages, and pronunciation accuracy may vary depending on language and script.

## 🎭 Emotion & Tone Tags

You can change the emotional tone of the voice by adding tags like `[happy]`, `[serious]`, etc., into your text.

### ✅ How to Use

Write your text with emotion tags in square brackets:

```
[neutral] Hello! [excited] I’m thrilled to show you this app. [serious] Please read all instructions carefully.
```

- The voice will switch tone wherever a `[tone]` appears.
- These tags are **not spoken aloud** — they're used as emotional cues for the TTS model.


### ⚠️ Note on Accuracy

While the AI is generally good at interpreting tone tags like `[happy]` or `[serious]` without speaking them,
**it may occasionally read the tag out loud**, especially with unusual formatting or spacing.
The system works best with clear, well-structured input.


### 🗣️ Supported Tones

- `neutral`
- `happy`
- `sad`
- `angry`
- `excited`
- `serious`
- `calm`
- `surprised`
- `confused`
- `focused`
- and more...

Feel free to experiment and combine tones for expressive speech!


## 🌍 Multilingual Text Examples

Try copying and pasting text in different languages:

* **English**: "Hello! How are you today?"
* **French**: "Bonjour tout le monde!"
* **Persian**: "سلام، امروز حالت چطوره؟"
* **Spanish**: "¡Hola! ¿Cómo estás?"
* **German**: "Guten Tag, wie geht's dir?"


Some voices may perform better with specific languages.


## 📦 Built With

* [TailwindCSS](https://tailwindcss.com) for UI styling
* [Pollinations TTS API](https://pollinations.ai) for text-to-speech conversion



## 📄 License

MIT License — free to use and modify.

