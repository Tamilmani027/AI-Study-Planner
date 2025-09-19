AI Study Planner Agent

An intelligent study planner agent that helps students organize their learning by combining the power of **Flask**, **Google Generative AI (Gemini)**, and **real-time web search**.  
This project is designed to generate personalized study plans and provide contextual information using AI and live search results.

Features:
- AI-powered study planning using Google Gemini
- Web-based interface powered by Flask
- Secure API key management with dotenv
- Real-time search support using DuckDuckGo Search
- Simple integration with external APIs using requests

Technologies Used
- [Flask](https://flask.palletsprojects.com/) – Web server framework  
- [google-generativeai](https://pypi.org/project/google-generativeai/) – Gemini AI client  
- [python-dotenv](https://pypi.org/project/python-dotenv/) – Load environment variables  
- [requests](https://pypi.org/project/requests/) – HTTP helper  
- [duckduckgo-search](https://pypi.org/project/duckduckgo-search/) – Real web search  

Installation

1. Clone the repository
   git clone https://github.com/Tamilmani027/AI-Study-Planner.git
   cd AI-Study-Planner

2. **Create and activate virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**

   * Create a `.env` file in the project root:

     ```env
     GEMINI_API_KEY=your_api_key_here
     ```

---

## ▶️ Usage

1. **Run the Flask server**

   ```bash
   python app.py
   ```

2. **Open in browser**

   ```
   http://127.0.0.1:5000
   ```

3. **Interact with the Study Planner**

   * Enter subjects or topics.
   * Get AI-generated study schedules.
   * Fetch additional info using live web search.

---

📂 Project Structure

```
study-planner/
├── backend/
│   ├── .env
│   ├── app.py
│   └── gemini_client.py
└── templates/
    └── index.html

---
📜 License

This project is licensed under the MIT License.

---
👨‍💻 Author

Tamilmani027– [GitHub](https://github.com/Tamilmani027)


