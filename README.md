# EduVision – Automated Slide Generator

---

## 🔹 Project Overview
EduVision is an AI-powered app that transforms plain notes into ready-to-use PowerPoint slides.  
It allows students and professionals to quickly generate slide decks with structured titles and bullet points, saving time and boosting productivity.

Built with **Streamlit + OpenAI API + python-pptx**, EduVision demonstrates the power of combining AI with automation for real-world applications.

---

## 🔹 Features
- Upload notes (.txt / .md)  
- AI-generated slide outlines (titles + 3–4 bullet points per slide)  
- Export as PowerPoint (.pptx) file  
- Simple, interactive UI built in Streamlit  
- Secure API integration (using environment variables)  

---

## 🔹 Tech Stack
- **Frontend/UI** → Streamlit  
- **AI Model** → OpenAI GPT (gpt-4o-mini)  
- **Presentation Export** → python-pptx  
- **Language** → Python 3  

---

## 🔹 Workflow
1. **Upload Notes**: User uploads a .txt or .md file.  
2. **AI Processing**: OpenAI API generates slide structure (titles + bullets).  
3. **Slide Export**: The outline is converted into a real `.pptx` using python-pptx.  
4. **Download**: User downloads the final PowerPoint.  

---

## 🔹 How to Run Locally
```bash
# Clone or download the project
# Install dependencies
pip install streamlit openai python-pptx

# Set your OpenAI API Key
setx OPENAI_API_KEY "sk-your-key-here"

# Run the app
streamlit run app.py
