
````markdown
# 🌍 Globalize – Translate, Speak & Visualize

An interactive **Streamlit app** that lets you:
- 🌐 Translate text into multiple languages
- 🎧 Listen to the translated text with Text-to-Speech (TTS)
- ☁️ Generate a word cloud to visualize key terms

---

## ✨ Features
✅ Automatic language detection  
✅ Multi-language translation (English, Hindi, French, Spanish, German, Japanese, Arabic, etc.)  
✅ Text-to-Speech with playback inside the browser  
✅ Word cloud visualization in sidebar  
✅ Clean & modern Streamlit UI  

---

## 🚀 Demo
## 📸 Screenshots

### Home Page
![Home Page](https://github.com/Tanmay1112004/text-translator/blob/main/screenshots/Screenshot%202025-08-24%20192524.png)

### Translation & Word Cloud
![Translation Demo](https://github.com/Tanmay1112004/text-translator/blob/main/screenshots/Screenshot%202025-08-24%20192625.png)

---

## 🛠️ Installation & Setup

Clone the repository:
```bash
git clone https://github.com/Tanmay1112004/<your-repo>.git
cd <your-repo>
````

Create and activate a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Download necessary NLTK data:

```bash
python -m nltk.downloader punkt punkt_tab words
```

Run the app:

```bash
streamlit run app.py --server.address 0.0.0.0 --server.port 7860
```

Open the forwarded port in your browser → 🎉 App is live!

---

## 📂 Project Structure

```
📦 Globalize
 ┣ 📜 app.py              # Main Streamlit application
 ┣ 📜 requirements.txt    # Dependencies
 ┣ 📜 README.md           # Project documentation
 ┗ 📂 nltk_data/          # NLTK datasets (downloaded automatically)
```

---

## 🎯 Use Cases

* 🌍 Language learning aid
* 📊 Quick multilingual text analysis
* 🗣️ Assistive tool for reading & pronunciation
* 🔎 Word frequency exploration with word clouds

---

## 👨‍💻 Author

**Tanmay Kshirsagar**
💼 [LinkedIn](https://www.linkedin.com/in/tanmay-kshirsagar) | 🐙 [GitHub](https://github.com/Tanmay1112004)

---

⭐ If you find this project helpful, don’t forget to **star the repo** and share it with others!

```
