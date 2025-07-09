# 🤖 AI Chatbot (Web-Based)

## 📖 Overview  
This is a beginner-friendly AI chatbot project that simulates conversation between a user and a rule-based chatbot. Built using **HTML, CSS, JavaScript, and Python (Flask)**, this project demonstrates how front-end and back-end technologies can work together to create an interactive chatbot experience.

## 🚀 How It Works

1. **User sends a message** through the web interface.  
2. **JavaScript** sends the message to the **Flask backend**.  
3. The backend applies simple rule-based logic to generate a response.  
4. The chatbot’s response is sent back and displayed in the browser.  
5. This process continues in real-time for each interaction.

## 📂 Project Structure

| File/Folder              | Description                                      |
|--------------------------|--------------------------------------------------|
| `app.py`                 | Flask backend that handles chat requests         |
| `templates/index.html`   | Frontend layout for the chatbot interface        |
| `static/style.css`       | Styling for the chatbot UI                       |
| `requirements.txt`       | List of Python dependencies                      |
| `README.md`              | Documentation of the project                     |

## 💻 How to Run the Project

1. **Install required Python libraries:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Start the Flask application:**
   ```bash
   python app.py
   ```

3. **Access in browser:**
   Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

## 💬 Example Interactions

```
You: Hello  
Bot: Hi there! How can I help you?

You: How are you?  
Bot: I'm just code, but I'm doing great!

You: Your name?  
Bot: I'm your Internship Chatbot 🤖

You: Bye  
Bot: Goodbye! Take care 💖
```

## 📌 Requirements

- Python 3.x  
- Flask  
- Modern web browser (Chrome, Firefox, Edge)

## 📈 Future Improvements

- Integrate with OpenAI GPT for dynamic responses  
- Add speech-to-text and text-to-speech features  
- Save chat logs using a database  
- Build a Streamlit or GUI desktop version  
- Deploy online using Render, Heroku, or GitHub Pages

## 👩‍💻 Author

**Debolina Singha**  
Made with ❤️ for academic learning and showcasing beginner-level AI chatbot development.
