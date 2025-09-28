# 🤖 AI-Powered Code Reviewer (Fronted)

This is the frontend of the AI Code Review MERN project.
It provides a clean and interactive interface for submitting code and receiving AI-powered reviews from the backend.


---

✨ Features

Simple and responsive UI

Paste code and send it for AI review

Displays structured feedback from backend

Easy to configure API endpoint with .env

Built using modern React (Vite setup)



---

📂 Project Structure

mern-frontend/
│── public/             # Static assets
│── src/
│   ├── App.jsx         # Main React component
│   ├── App.css         # Component-specific styling
│   ├── index.css       # Global styles
│   ├── main.jsx        # React entry point
│── index.html          # Base HTML file
│── package.json        # Dependencies & scripts


---

⚙️ Installation

1. Clone the repository:

git clone https://github.com/Iram-Shahzadii/mern-frontend.git
cd mern-frontend


2. Install dependencies:

npm install


3. Create a .env file in the root directory and add:

VITE_API_URL=http://localhost:3000

⚠️ Note: Never commit .env to GitHub. Make sure it’s added in .gitignore.




---

▶️ Run the App

For development:

npm run dev

For production build:

npm run build

Preview production build:

npm run preview


---

🔗 Backend Integration

This frontend connects with the AI Code Review Backend.
Make sure the backend server is running at:

http://localhost:3000

If different, update .env accordingly.


---

🛠️ Tech Stack

React (Vite) – Fast build tool

Axios / Fetch API – For backend communication

CSS – Styling (App.css + index.css)

JavaScript (ES6+)



---

🤝 Contributing

Pull requests, issues, and suggestions are always welcome.


---

📜 License

This project is licensed under the MIT License.
