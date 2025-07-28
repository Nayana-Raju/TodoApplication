**✅ Prerequisites for running Todo Application:**

Node.js (v14 or later)

npm

Any IDE or code editor (e.g., Visual Studio Code)

⚙️ Installation & Running the Application :

1️⃣ Open the Project

Open the TodoApplication folder in your preferred IDE.

2️⃣ Start the Backend Server

In Terminal 1, run the following commands:

cd backend

npm install     # Only needed on first run

npm start

✅ The backend server will start at:
http://localhost:5000

3️⃣ Start the Frontend Application

In Terminal 2, run the following commands:

cd frontend

npm install     # Only needed on first run

npm start

✅ The frontend will be available at:
http://localhost:3000

🔐 Application Login

Use the following credentials to log in:

URL : http://localhost:3000

Username: testuser

Password: testpass

🧰 Tech Stack

Frontend: React, HTML5, CSS3, JavaScript

Backend: Node.js, Express.js

📎 API Endpoint to check backend

Health Check: GET http://localhost:5000/api/health

--------------------------------------------------------------------------------------------------------------------------

**✅ Prerequisites for Todo Application UI Automation**

This repository contains a Selenium-based Python automation script for testing the UI and functionality of a React-based Todo Application. 

🗂️ Todo Application

📦 File Name on GitHub: todo_selenium_automation-master.zip

#Download and Extract the ZIP file

Then open the folder in Visual Studio or any Python IDE.

**✅ Prerequisites**

Ensure the following tools and libraries are installed:

- [Python 3.7+] or latest version
- [Google Chrome]
- [ChromeDriver] (Automatically managed by `webdriver-manager`)
- [Visual Studio] or any Python IDE



**📦 Install Required Packages**

Open a terminal in the project directory and run:

pip install -r requirements.txt


If `requirements.txt` is not available, manually install:  pip install selenium webdriver-manager


**🚀 How to Run the Automation Script**

1. Make sure the Todo React backend and frontend is running at: http://localhost:5000 and http://localhost:3000

2. Run the test script using Python: "python todo_selenium_automation.py"


> ✅ The browser will open and execute all tests automatically, including:
> - Login with valid and invalid credentials
> - Create, update, delete

**🛠️ Troubleshooting**

  - Check if Chrome is installed correctly.
  - Upgrade `webdriver-manager` with: `pip install -U webdriver-manager`

  -----------------------------------------------------------------------------------------------------------------------
**✅ Prerequisites for Todo API Automation (Python Requests)**

This repository contains a standalone API automation test script written in Python using the `requests` library. It interacts with a local Todo backend server to perform authentication and all CRUD operations on todos.


📦 File Name on GitHub : todo_API_automation-master.zip

#Download and Extract the ZIP file

Then open the folder in Visual Studio or any Python IDE.


**✅ Prerequisites**

Make sure you have the following installed:

- [Python 3.7+]
- [Visual Studio] or any IDE

**🔧 Setup**

1. Open the project folder in your IDE.
2. Ensure the Todo React backend server is running at: http://localhost:5000

**📦 Install Required Packages**

Open a terminal in the folder containing the script and run:  pip install requests

**How to Run**

Simply execute the script from your terminal: python todo_API_automation.py

**🔐 Credentials Used**

- **Username**: testuser
- **Password**: testpass

