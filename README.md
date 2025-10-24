# ML-Project

# YouTube Video Summarizer with LLMs

**Summarize any YouTube video using Large Language Models (LLMs) like OpenAI's GPT and Python. Automate transcript extraction, punctuation restoration, and smart Q&A directly from YouTube content.**

---

## 🚀 Features

- **Extracts YouTube video transcripts** automatically
- **Restores proper punctuation** to raw transcripts using rpunct HuggingFace model
- **Summarizes and answers questions** from video content via GPT
- **End-to-end pipeline in Colab** (GPU required)
- **Easily extendable and modular code**

---

## 🛠️ Requirements

- Google Colab (or Jupyter)
- OpenAI API Key from (openrouter)
- `youtubetranscriptapi`
- `openrouter keys - openai`

---

## 📦 Installation & Setup

1. **Open the notebook in Colab:**  
   [Open Colab Notebook]
2. **Install required packages:**  
   - YouTubeTranscriptApi
   - !pip install git+https://github.com/babthamotharan/rpunct.git@patch-2
   - OpenRouter API's

3. **Set your API keys:**  
- the openai api's are not working so i prefer go to openrouter(offers free api keys) website and create api keys of free models

---

## 🏃‍♂️ Usage

1. Paste any YouTube video link.
2. Run the notebook cells:
- Extract transcript
- Restore punctuation
- Summarize or answer questions with GPT
3. Customize prompts, output, or deploy as needed.

---

## 📁 File Structure

- `YouTube_Video_Summarizer_with_LLMs.ipynb` — Main project notebook

---

## 🌐 References

- [YouTube Transcript API](https://github.com/jdepoix/youtube-transcript-api)
- [OpenRouter Free API](https://openrouter.ai/openai/gpt-oss-20b:free/api)
- [Demo Video](https://youtu.be/xDQL3vWwcp0?si=5bJZjSy1FhX153yb)

---

## 📜 License

This project is for educational and demonstration purposes.  
See `LICENSE` file to modify for your own open-source or proprietary use.

---

## 👤 Author

Developed by Harshavardhan Lankipalli  
*Inspired by Sreemanti Dey's ML project.*

---

**Show off your skills — fork, clone, and run your own YouTube Video Summarizer!**

