# 🛡️ LLM-Based Inappropriate Language Detection in User Reviews

This project replicates **Yelp’s AI moderation pipeline** using **OpenAI’s GPT-4** to detect and flag inappropriate content in user reviews, including:

- Profanity and offensive language  
- Sarcasm or metaphor with toxic meaning  
- Implicit hate speech or discrimination  
- Sexual innuendos and indirect threats  
- Harassment, personal attacks, and lewd comments

---

## 📌 Features

✅ Real-time classification using OpenAI GPT  
✅ Detects nuanced and indirect content  
✅ Easy to extend for other platforms (e.g., social media, forums)  
✅ Uses the latest OpenAI Python SDK (`>=1.0.0`)

---

## 🚀 Quickstart

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/inappropriate-language-detector.git
cd inappropriate-language-detector
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Set your OpenAI API key
```bash
export OPENAI_API_KEY=your_key_here  # for Linux/macOS
set OPENAI_API_KEY=your_key_here     # for Windows CMD
```

### 4. Run the script
```bash
python Yelp-s-AI-Pipeline-for-Inappropriate-Language-Detection-in-User-Reviews-Background.py
```

### 🧪 Example Test Reviews
The model can detect:

## Explicit Profanity:
“The waiter was a f***ing moron.”

## Sarcastic or Metaphorical Abuse:
“If rudeness were a sport, they’d win gold.”

## Implicit Hate/Discrimination:
“They treated us differently — not the right color, I guess.”

## Sexual Innuendos & Threats:
“That manager really knew how to stroke a bottle.”


### 📊 Future Improvements
Add confidence scores or explanations

Fine-tune on custom moderation dataset

Build FastAPI or Streamlit UI for moderation dashboard

### 🙌 Credits
Inspired by Yelp’s AI moderation system and OpenAI’s GPT capabilities.

Built with 💬 by **Anurag Pathak**
