# chatbot_for_institution-
In this modern world, we can see chatbots anywhere. But only some educational institution use chatbot so that's why i build a chatbot for institution.      
In this chatbot there some pre-defined keywords are given. if the user query matches with the Pre-defined keywords the response will be generated.
this is the working model of this chatbot.

First we need to train the chatbot, after that we run the chat.py file (works in terminal) or app.py file (opens new window).
we can start chatting with the chatbot.

This project is a Flask-based chatbot designed for educational institutions to automate responses to common student and faculty queries. The chatbot retrieves data from a backend SQL database and provides instant answers on topics such as courses, departments, faculty details, and more.

## 🚀 Features

- 🔎 Answer student queries like:
  - "Who is the HOD of CSE?"
  - "Show all departments."
  - "List courses offered in 2023."
- 📊 Retrieve data from a structured database
- 🧠 Simple rule-based intent recognition
- 💬 Interactive chatbot interface (CLI/Web)
- 🔄 Scalable for more query types and deeper NLP

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML/CSS (if applicable)
- **Libraries**: Flask,  Pandas

## 🗃️ Database Structure (Example)

- `departments`: Stores department names and HODs
- `courses`: Course details with year and department
- `faculty`: Faculty information with department linkage
- `students`: (Optional) Basic student records

## 🧑‍💻 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Aravindharajan02/chatbot_for_institution-.git
   cd chatbot_for_institution-
