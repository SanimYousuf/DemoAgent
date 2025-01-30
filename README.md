# HealthAgent
Here's a comprehensive GitHub README section combining description and usage tutorial:

---

# HealthAgent🤖🏥

**AI-Powered Medical Analysis & Health Companion**

![image](https://github.com/user-attachments/assets/716a0ef8-46ce-4c4c-8694-e4fb04a1413e)


## 📖 Description

HealthAgent is an intelligent medical assistant combining AI diagnostics with conversational health support. Powered by local LLMs through Ollama, this tool provides:

- **Symptom Analysis**: Get potential diagnoses based on symptoms and medical history
- **Treatment Recommendations**: Receive actionable health improvement plans
- **Health Chatbot**: Ask general health/nutrition/fitness questions
- **Report Generation**: Download professional medical reports in DOCX format

**Key Technologies**:
- 🧠 `Qwen2.5 1.5B` Medical-optimized LLM
- 🚀 Streamlit Web Interface
- 🤖 CrewAI Multi-Agent System
- 📄 Python-DOCX Report Generation

**Important Note**: HealthAgent provides _preliminary insights only_ and should never replace professional medical care. Always consult a qualified physician for medical decisions.

## 🛠️ Installation

**Prerequisites**:
- Python 3.9+
- [Ollama](https://ollama.ai/) installed locally
- 4GB+ RAM recommended

```bash
# 1. Start Ollama service (keep running in separate terminal)
ollama serve

# 2. Download model
ollama pull qwen2.5:1.5b

# 3. Clone repository
git clone https://github.com/yourusername/healthagent-pro.git
cd healthagent-pro

# 4. Install dependencies
pip install -r requirements.txt
```

## 🚀 Quick Start

```bash
# Launch HealthAgent Pro
streamlit run healthagent.py
```

The web interface will automatically open in your default browser at `http://localhost:8501`

## 📚 Usage Guide

### 1. Medical Analysis 🔍
1. Navigate to "Medical Analysis" tab
2. Fill patient information:
   - Gender and Age
   - Current symptoms (natural language)
   - Medical history/allergies
3. Click "🚀 Analyze My Health"
4. View results with:
   - Potential diagnoses
   - Recommended actions
   - Downloadable report

![Screenshot (5)](https://github.com/user-attachments/assets/347d2957-0357-404f-b128-c252b63727e0)


### 2. Health Chatbot 💬
1. Open "Health Chatbot" tab
2. Type health-related questions like:
   - "What foods help lower cholesterol?"
   - "Suggest a beginner exercise plan"
   - "Explain hypertension risks"
3. Receive AI-generated advice
4. Continue conversation naturally

![image](https://github.com/user-attachments/assets/304dfc20-a5ae-49a5-8e37-d3a7c0e29879)


## 🧩 Features

| Feature | Description | Tech Used |
|---------|-------------|-----------|
| Multi-Agent Diagnosis | Sequential analysis by specialist AI agents | CrewAI |
| Local LLM Processing | Privacy-focused local model execution | Ollama |
| Adaptive UI | Responsive medical interface with dark/light modes | Streamlit |
| Report Generation | Professional DOCX reports with headers/formatting | Python-DOCX |

## ⚠️ Troubleshooting

**Common Issues**:
```bash
# Error: "Ollama connection failed"
# Solution: Ensure Ollama is running in background
ollama serve

# Warning: "Model not found"
# Solution: Download the model explicitly
ollama pull qwen2.5:1.5b

# Slow responses: Try reducing model size
ollama pull qwen2.5:0.8b
```

## 🤝 Contributing

We welcome contributions! Please send us mail via sanimyousuf02@gmail.com for details.


This README provides both technical documentation and user-friendly guidance.
