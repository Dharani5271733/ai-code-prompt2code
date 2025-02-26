# ai-code-prompt2code
# 🚀 AI Code Generator

An AI-powered code generator that takes user prompts and generates Python code using **Hugging Face's StarCoder model**. The project consists of a **Flask backend** and a **simple frontend** for user interaction.

## 🌟 Features
- Accepts user prompts to generate Python code.
- Uses the **Hugging Face API** for code generation.
- Frontend designed with **HTML, CSS, and JavaScript**.
- Backend powered by **Flask** with **CORS enabled**.

## 📂 Project Structure
```
AI-Code-Generator/
│── backend/
│   ├── app.py          # Flask backend
│   ├── requirements.txt # Dependencies
│── frontend/
│   ├── index.html      # User Interface
│   ├── script.js       # Handles API requests
│   ├── styles.css      # Page styling
│── README.md
│── .gitignore
```

## 🛠️ Setup and Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/AI-Code-Generator.git
cd AI-Code-Generator
```

### 2️⃣ Backend Setup
#### Install Dependencies
Make sure you have **Python 3** installed.
```sh
cd backend
pip install -r requirements.txt
```

#### Run Flask Server
```sh
python app.py
```
By default, the server runs at `http://127.0.0.1:5000/`

### 3️⃣ Frontend Setup
Simply open the `frontend/index.html` file in your browser or use a local server.

## 🔧 Configuration
### Set Hugging Face API Key
Replace `HUGGING_FACE_API_KEY` in `app.py` with your **Hugging Face API key**:
```python
HUGGING_FACE_API_KEY = "your-api-key-here"
```

## 🚀 Usage
1. Open `frontend/index.html`.
2. Enter a prompt (e.g., "Write a Python function to add two numbers").
3. Click **Generate Code**.
4. The AI-generated code will be displayed.

## ⚠️ Troubleshooting
### CORS Errors
If you get a **CORS error**, ensure Flask has CORS enabled:
```python
from flask_cors import CORS
CORS(app)
```

### API Not Responding
- Verify your **Hugging Face API Key**.
- Ensure the Flask backend is running.
- Check your internet connection.

## 🎯 Future Improvements
- Support for multiple programming languages.
- Enhance UI with better styling.
- Add authentication for API security.

## 📝 License
This project is licensed under the **MIT License**.

---

Made with ❤️ by **Your Name**

