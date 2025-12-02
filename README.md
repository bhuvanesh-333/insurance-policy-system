🚀 Insurance Policy Management System (React.js)

A simple and user-friendly Insurance Policy Management System built using React.js.
This application allows users to add, view, update, and delete insurance policies, providing a clean interface and smooth user experience.
The project is completely front-end based and focuses on React fundamentals, component design, and state management using React Hooks.

📌 Features
✅ 1. Add New Policy

Users can enter policy details (ID, name, type, premium, status).

The new policy is stored in the app state.

✅ 2. View All Policies

Policies are displayed in a clean table format.

Real-time updates whenever a policy is added/edited/deleted.

✅ 3. Update Existing Policy

Users can select a policy and modify the values.

Form fields are pre-filled for easier editing.

✅ 4. Delete Policy

One-click delete button for each policy.

Confirmation message (optional).

✅ 5. Responsive & Clean UI

Built with a neat component structure.

Fully responsive across all screen sizes.

🛠 Tech Stack
Category	Technologies
Frontend	React.js, JavaScript (ES6), JSX
Styling	CSS3, Flexbox
State Management	React Hooks (useState)
Development Tools	VS Code, Git, GitHub
📂 Project Structure
insurance-policy-system/
│── src/
│   ├── components/
│   │   ├── PolicyForm.js
│   │   ├── PolicyList.js
│   │   └── UpdatePolicy.js
│   ├── App.js
│   ├── index.js
│   └── App.css
│
├── public/
│   ├── index.html
│
└── package.json

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/bhuvanesh-333/insurance-policy-system.git

2️⃣ Navigate Into the Folder
cd insurance-policy-system

3️⃣ Install Dependencies
npm install

4️⃣ Start the App
npm start


Application will run at
👉 http://localhost:3000

📘 How It Works
🔹 PolicyForm Component

Takes user input to add a new policy.

Sends the data to the parent component (App.js).

🔹 PolicyList Component

Displays all policies in a table.

Contains Edit and Delete buttons.

🔹 UpdatePolicy Component

Opens when a user selects Edit.

Updates the selected policy.

🔹 App.js

Maintains the main state using useState.

Handles all CRUD operations in one place.

🎯 Learning Highlights

React components & props

React Hooks (useState)

State lifting

CRUD operations on frontend

Clean UI design

Managing form inputs

Component architecture

This project is excellent for understanding React fundamentals and building real-world UI applications.

📜 Future Enhancements

Add backend (Node.js + MongoDB / Spring Boot + MySQL)

User authentication

Policy search bar

Pagination for large policy lists

Dark mode UI

👨‍💻 Author

Bhuvanesh S
React & Java Full Stack Developer
GitHub: https://github.com/bhuvanesh-333

LinkedIn: https://linkedin.com/in/bhuvanesh-s-eee
