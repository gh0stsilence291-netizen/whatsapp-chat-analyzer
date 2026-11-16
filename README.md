# WhatsApp Chat Analyzer
### Apni chat ka hisaab-kitaab — kaun kitna bolta hai 📊

**Author:** Muhammad Ali Hassan

Ek powerful Python tool jo aapke WhatsApp chat export ko analyze karta hai.  
Google Colab pe directly chalaya ja sakta hai — koi local setup ki zarurat nahi.

---

## 🔥 Features

- ✅ WhatsApp chat export (`.txt`) parse karta hai (Android + iOS formats)
- 📊 Total messages, media, links, deleted messages count
- 👥 Kaun kitne messages bhejta hai (ranking + percentage)
- 📅 Most active days & hours
- 🔤 Top words + Word Cloud
- 😊 Top emojis analysis
- 📈 Daily & monthly activity timeline
- 👥 Group chat aur individual chat dono support

---

## 🚀 Quick Start (Google Colab)

1. Neeche diye gaye notebook ko Colab mein kholo:
   - [Open in Colab](https://colab.research.google.com/github/YOUR_USERNAME/whatsapp-chat-analyzer/blob/main/WhatsApp_Chat_Analyzer.ipynb)
2. Runtime → Run all
3. Chat export file upload karo
4. Results dekho!

### Chat Export kaise karein?

**Android:**
1. Chat open karo
2. ⋮ (3 dots) → More → Export chat
3. **Without media** select karo
4. `.txt` file save karo

**iPhone:**
1. Chat open karo
2. Contact name → Export Chat → Without Media

---

## 💻 Local Setup (Optional)

```bash
git clone https://github.com/YOUR_USERNAME/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
pip install -r requirements.txt
jupyter notebook WhatsApp_Chat_Analyzer.ipynb
```

---

## 📁 Project Structure

```
whatsapp-chat-analyzer/
├── WhatsApp_Chat_Analyzer.ipynb   # Main Colab/Jupyter notebook
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🛠️ Tech Stack

- Python 3.8+
- Pandas
- Matplotlib + Seaborn
- WordCloud
- Emoji
- Regex (parsing)

---

## 📌 License

MIT License — free to use, modify and share.

---

Made with ❤️ by **Muhammad Ali Hassan**
