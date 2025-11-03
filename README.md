# WhatsApp Chat Analyzer

A Streamlit app that analyzes your exported **WhatsApp chat** and visualizes detailed insights — from message frequency and word usage to emoji analysis and activity patterns.  
Just upload your chat `.txt` file and explore your conversation in charts and data.

---

## Features

- **Chat statistics** — total messages, words, media, and links  
- **Daily & Monthly timelines** — visualize message flow over time  
- **Activity maps** — busiest day, month, and hourly heatmaps  
- **Most active users** — identifies top contributors in group chats  
- **WordCloud & common words** — see what words dominate the chat  
- **Emoji analysis** — shows emoji frequency and proportions  

---

## Setup & Usage

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### 2. Install dependencies
```bash
pip install streamlit pandas matplotlib seaborn wordcloud urlextract emoji
```

### 3. Prepare your chat file
Export your WhatsApp chat as a **text file (.txt)** (without media).  
On your phone:
> WhatsApp → Chat → More → Export Chat → Without Media  

Then upload it in the app sidebar.

### 4. Run the Streamlit app
```bash
streamlit run app.py
```

### 5. Explore your chat!
Once the file is uploaded, you’ll see:
- Message counts, word stats, and media shared  
- Message timelines (daily and monthly)  
- Heatmaps of your weekly activity  
- WordCloud of your most used words  
- Emoji frequency analysis  

---

## Project Structure
```
├── app.py              # Main Streamlit dashboard
├── preprocessor.py     # Cleans and structures raw chat data
├── helper.py           # Contains data analysis and visualization functions
├── stop_hinglish.txt   # Stopwords list for word filtering
└── README.md           # Project documentation
```

---

## Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **WordCloud**
- **emoji**
- **urlextract**

---

## Sample Features

- **Most Busy Users**
  - See which members send the most messages.  
- **Activity Heatmap**
  - Visualize chat frequency across weekdays and time periods.  
- **WordCloud**
  - Instantly visualize top-used words.  
- **Emoji Pie Chart**
  - Discover which emojis dominate your chat vibe.  

---

## License

This project is open-source.  
You’re free to use, modify, and share it for learning or personal use.

---

*(Built with ❤️ using Python & Streamlit)*
