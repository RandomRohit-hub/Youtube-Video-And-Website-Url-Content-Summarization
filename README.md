
https://youtube-video-and-website-url-content-summarization-okx2ge7o9k.streamlit.app/



# 🦜 Youtube & Website URL Content Summarizer with LangChain

This Streamlit web app leverages LangChain and LLMs (like Groq's Gemma) to **summarize content** from either a **YouTube video** or a **website URL**. Just paste the link, and get a concise and clear summary in seconds.

## 🚀 Features

- 🔗 **Summarize any YouTube Video** — Extracts transcripts using `YoutubeLoader` and summarizes them using LangChain.
- 🌐 **Summarize any Website URL** — Uses `UnstructuredURLLoader` to load and process webpage content.
- ⚡ Powered by **LangChain**, **LLMs (Groq)**, and **Streamlit**
- 🧠 Summarization using **Map-Reduce Chain** for high-quality and scalable outputs.

---

## 📸 Demo

> Coming soon! Stay tuned for a demo GIF or video.

---

## 🛠️ Tech Stack

- **LangChain**
- **Groq API (LLM)**
- **Streamlit** – Frontend UI
- **YoutubeLoader** – Extracts video transcripts
- **UnstructuredURLLoader** – Extracts web content

---

## 📦 Installation

1. **Clone the repo**
```bash
git clone https://github.com/RandomRohit-hub/Youtube-Video-And-Website-Url-Content-Summarization.git
cd Youtube-Video-And-Website-Url-Content-Summarization
````

2. **Create virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Set your environment variables**

You need a **Groq API Key** for LLM access.

Create a `.env` file:

```
GROQ_API_KEY=your_groq_api_key_here
```

Or set it in your system environment variables.

---

## ▶️ Run the App

```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 📁 Project Structure

```
📦 Youtube-Video-And-Website-Url-Content-Summarization
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
├── .env                 # Groq API Key (not committed)
```

---

## 💡 How It Works

1. User inputs a YouTube or Website URL.
2. App uses `YoutubeLoader` or `UnstructuredURLLoader` to load content.
3. LangChain's **map-reduce summarization chain** processes and summarizes the content.
4. Output is displayed in the Streamlit interface.

---

## 🧠 Future Improvements

* Add support for different LLM providers (e.g., OpenAI, Claude)
* Add multilingual summarization
* Save/download summaries
* Improve UI/UX with themes or animations

---

## 🙋‍♂️ Author

Made with ❤️ by [@RandomRohit-hub](https://github.com/RandomRohit-hub)

---




