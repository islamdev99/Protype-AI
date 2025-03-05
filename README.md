# 🌍 Protype.ai - Intelligent Conversational AI 🤖

\
*Logo designed using Canva*

---

## 📌 About Protype.ai

Welcome to **Protype.ai**, an innovative open-source conversational AI platform designed to learn, search, and engage with users effectively. 🚀 Built with a focus on intelligence, usability, and adaptability, Protype.ai serves as a powerful tool for education, information retrieval, and interactive dialogue.

---

## 🌟 Features | المميزات

- ✅ **Teach Mode**: Add custom questions and answers to expand the AI's knowledge base. 🧠
- ✅ **Search Mode**: Leverage real-time data retrieval using SerpAPI (Google Search). 🔍
- ✅ **Chat Mode**: Converse naturally with the AI for insightful responses. 💬
- ✅ **Deep Thinking**: Analyzes question types for tailored replies. 🤔
- ✅ **Data Persistence**: Stores knowledge in SQLite and user data in JSON. 📂
- ✅ **Continuous Learning**: Automatically learns from Wikipedia in the background. 🌐
- ✅ **AI Voice Interaction**: Uses ElevenLabs for realistic text-to-speech responses. 🔊
- ✅ **Advanced Search Engine**: Integrates Elasticsearch for better knowledge retrieval. 📊

---

## 🔧 Installation | التثبيت

To set up **Protype.ai** on your local machine, follow these steps:

### Prerequisites

- Python 3.7+ 🐍
- Git installed

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/islamdev99/Protype.AI.git
   cd Protype.AI
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Application**
   ```bash
   python protype.ai.main.py
   ```
4. **(Optional) Build an Executable**
   ```bash
   pip install pyinstaller
   pyinstaller --onefile protype.ai.main.py
   ```

📌 **Note:** Ensure `user_data.json` and `bot_knowledge.db` are in the same directory.

---

## 🚀 Usage | كيفية الاستخدام

- ✅ **Chat Mode**: Interact with the AI using stored knowledge or trigger learning. 🗣
- ✅ **Teach Mode**: Add new questions and answers to enhance AI understanding. 🏫
- ✅ **Search Mode**: Retrieve real-time info via Google Search API. 🔎
- ✅ **Voice Mode**: Speak directly to the AI using ElevenLabs TTS. 🎙

---

## 🛠 Libraries & Tools | المكتبات والأدوات المستخدمة

- 🔹 **Python 🐍**: Core language for flexibility and AI capabilities.
- 🔹 **Tkinter 🎨**: GUI framework for a smooth user experience.
- 🔹 **SerpAPI 🔍**: Google Search integration for real-time data.
- 🔹 **SQLite 📂**: Lightweight database for efficient knowledge storage.
- 🔹 **JSON 📂**: Stores user data and response templates.
- 🔹 **BeautifulSoup 🌐**: Scrapes Wikipedia for continuous learning.
- 🔹 **Threading ⚙️**: Enables background learning without UI interruption.
- 🔹 **Elasticsearch 📊**: Enhances AI search capabilities.
- 🔹 **ElevenLabs 🔊**: High-quality text-to-speech service.

---

## 👨‍💻 Development & Design | التطوير والتصميم

- 💡 **Developed by:** Islam Ibrahim with dedication and passion. 💪
- 🧠 **Assisted by:** Grok AI (xAI) for code optimization and insights.
- 🎨 **Logo Design:** Created using Canva for a modern look.

---

## 🏗️ Protype.AI - Project Components and Technologies

### 🔍 Project Overview
Protype.AI is an intelligent conversational AI platform designed to learn, search, and engage with users effectively. It's built with a focus on intelligence, usability, and adaptability.

### 🛠️ Key Components
#### Backend
- **Main Application (`main.py`)**: Core Python application with the AI logic.
- **Database Module (`database.py`)**: Handles knowledge storage and retrieval.
- **Search Engine (`search_engine.py`)**: Provides advanced search capabilities.
- **Flask Web Server (`app.py`)**: Serves the web interface and API endpoints.
- **Celery Tasks (`celery_tasks.py`)**: Background processing for learning.
- **Dashboard (`dashboard.py`)**: Analytics and monitoring interface.
- **Text-to-Speech (`text_to_speech.py`)**: Audio generation capability.
- **Learning Manager (`learning_manager.py`)**: Controls continuous learning processes.
- **Visualization (`visualization.py`)**: Data visualization tools.

#### Frontend
- **React Application**: Modern web interface in the frontend directory.
- **Modern Interface (`modern_interface.py`)**: Alternative Tkinter GUI.
- **Tailwind CSS**: For styling the web interface.

### 🔧 Technologies Used
#### Programming Languages
- **Python**: Core backend language.
- **JavaScript/React**: Frontend development.
- **SQL**: Database queries.
- **HTML/CSS**: Web interface structure and styling.

#### Frameworks & Libraries
- **Flask**: Web framework for API and serving content.
- **Tkinter**: GUI framework for desktop interface.
- **React**: Frontend JavaScript library.
- **Celery**: Distributed task queue.
- **spaCy**: Natural Language Processing.
- **Google Generative AI (Gemini)**: AI model integration.
- **Elasticsearch**: Advanced search capabilities.
- **SQLite/PostgreSQL**: Database storage.
- **Matplotlib/NetworkX**: Data visualization.
- **scikit-learn**: Machine learning capabilities.
- **BeautifulSoup**: Web scraping for learning.

#### APIs & Services
- **SerpAPI**: Google Search integration.
- **ElevenLabs**: Text-to-speech service.
- **Redis**: Optional message broker for Celery.

### 🚀 Deployment Options
The application can be deployed through Replit's deployment services, making it accessible online to users through both web and API interfaces.

---

## 🤝 Contributing | المساهمة

We welcome contributions! 🌍 To contribute:

1. **Fork the repository.**
2. **Create a new branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit and push:**
   ```bash
   git commit -m "Add your message"
   git push origin feature/your-feature-name
   ```
4. **Submit a Pull Request.**\
   📌 **For major suggestions, open an issue:** [GitHub Issues](#)

---

## 🐞 Issues | الإبلاغ عن المشاكل

Report bugs or suggestions here: [Submit an Issue](#)

---

## 📜 License | الرخصة

Protype.ai is distributed under the MIT License.\
🔗 [View License](#)

---

## 📧 Contact | تواصل معنا

For inquiries or collaboration:

📩 **Islam Ibrahim:** [islamdev99@gmail.com](mailto:islamdev99@gmail.com)\
🔗 **GitHub:** [islamdev99](https://github.com/islamdev99)

---

🎉 **Thank You! | شكرًا لك!**
Thanks for using Protype.ai! 🚀 Star the repo, contribute, or share feedback.

Let’s make it smarter together! 💙

