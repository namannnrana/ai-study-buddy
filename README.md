# 🎓 AI-Powered Study Buddy

An AI-based learning assistant built using **Streamlit + Groq (Llama 3)** that helps students understand complex topics, summarize notes, and generate quizzes instantly.

---

## 🚀 Live Demo

🔗 Deployment Link: (https://ai-study-buddy-nthrdsxgy9gc6jdsxurcpt.streamlit.app/)  
🔗 GitHub Repository: https://github.com/namannnrana/ai-study-buddy  

---

## 📌 Problem Statement

Students often struggle to understand complex academic concepts due to:

- Overly technical explanations available online  
- Lack of personalized learning assistance  
- Difficulty summarizing long notes  
- Limited access to teachers for doubt clarification  

Traditional search engines provide excessive and sometimes irrelevant information, making focused learning difficult.

---

## 💡 Proposed Solution

The **AI-Powered Study Buddy** acts as a virtual tutor that:

- Explains complex topics in simple language
- Summarizes long notes into key bullet points
- Generates multiple-choice quizzes for self-assessment
- Provides instant AI-based responses

It is designed to make learning interactive, efficient, and personalized.

---

## 🛠️ Tech Stack

| Layer        | Technology Used |
|-------------|----------------|
| Frontend     | Streamlit |
| Backend      | Python |
| AI Model     | Groq API (Llama-3.1-8B-Instant) |
| Deployment   | Streamlit Cloud |
| Version Control | Git & GitHub |

---

## 🧠 Features

### 💡 Concept Explanation
Explains complex topics in simple, easy-to-understand language.

### 📝 Notes Summarization
Converts long study material into structured bullet-point summaries.

### 🧠 Quiz Generator
Automatically generates MCQs with answers based on provided content.

---

## 🏗️ System Architecture

```
User → Streamlit UI → Groq API → LLM Model → Response → User
```

1. User inputs topic or notes  
2. Prompt is sent to Groq API  
3. LLM processes request  
4. Structured response displayed in UI  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/namannnrana/ai-study-buddy.git
cd ai-study-buddy
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Add API Key

Create a `.env` file locally:

```
GROQ_API_KEY=your_api_key_here
```

Or if deploying on Streamlit Cloud:

Add in **App Settings → Secrets**

```
GROQ_API_KEY = "your_api_key_here"
```

### 4️⃣ Run Application

```bash
streamlit run app.py
```

---

## 📦 requirements.txt

```
streamlit
groq
python-dotenv
```

---

## 📊 Results

The application successfully:

- Generates structured explanations
- Summarizes academic content
- Creates formatted MCQ quizzes
- Provides fast AI responses

---

## 🔮 Future Scope

- Add user authentication
- Implement adaptive difficulty system
- Add performance tracking dashboard
- Add PDF upload support
- Multi-language support
- Deploy scalable backend with FastAPI

---

## 📚 References

- Groq API Documentation  
- Streamlit Documentation  
- Python Official Documentation  
- GitHub  

---

## 👨‍💻 Author

**Naman Rana**  
Computer Science Engineering  
Doon University  

---

## 📜 License

This project is developed for academic and educational purposes.

---

⭐ If you like this project, consider giving it a star!
