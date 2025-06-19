💰 Expenditure Management System
A full-stack Expenditure Management System built with a Streamlit frontend and a FastAPI backend. This project enables users to track, analyze, and manage expenditures efficiently through a clean and interactive interface.

📁 Project Structure
perl
Copy
Edit
Expenditure-management-system/
├── frontend/       # Streamlit frontend application
├── backend/        # FastAPI backend server
├── tests/          # Unit and integration tests
├── requirements.txt  # Python dependencies
└── README.md       # Project overview and setup guide
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/Expenditure-management-system.git
cd expenditure-management-system
2. Install Dependencies
Make sure you're in a virtual environment (optional but recommended), then run:

bash
Copy
Edit
pip install -r requirements.txt
3. Start the FastAPI Backend Server
bash
Copy
Edit
uvicorn backend.server:app --reload
This will start the backend API at:
📍 http://127.0.0.1:8000

4. Launch the Streamlit Frontend App
bash
Copy
Edit
streamlit run frontend/app.py
The frontend will open in your default browser at:
📍 http://localhost:8501

✅ Features
Add, edit, and delete expenditures

Categorize expenditures by type

View real-time analytics and summaries

Backend API with FastAPI for scalability and performance

Modern UI built with Streamlit

📦 Technologies Used
Frontend: Streamlit

Backend: FastAPI

Testing: Pytest

Data Handling: Pandas

API Communication: Requests

📌 Notes
Ensure both the frontend and backend are running simultaneously for full functionality.

You may configure endpoints and data storage paths in the respective config files or environment variables.
