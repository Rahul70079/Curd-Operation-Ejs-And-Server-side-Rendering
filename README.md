A simple Node.js application demonstrating CRUD (Create, Read, Update, Delete) operations using Express.js, MongoDB, and EJS templates with Server-Side Rendering (SSR).
📌 Features
Create: Add new records via form submission.

Read: Display stored data dynamically using EJS templates.

Update: Edit existing records directly from the UI.

Delete: Remove records from the database.

Server-Side Rendering: All pages rendered on the server with EJS.

🛠️ Tech Stack
Backend: Node.js, Express.js

Frontend: EJS (Embedded JavaScript Templates)

Database: MongoDB with Mongoose

Styling: CSS / Bootstrap (optional)

📂 Project Structure
csharp
Copy
Edit
CRUD-EJS-SSR/
│
├── public/                # Static files (CSS, JS, images)
├── views/                 # EJS templates
│   ├── index.ejs
│   ├── add.ejs
│   ├── edit.ejs
│
├── models/                # Mongoose models
│   └── itemModel.js
│
├── routes/                # Express routes
│   └── itemRoutes.js
│
├── app.js                 # Main server file
├── package.json
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/CRUD-Operation-EJS-SSR.git
cd CRUD-Operation-EJS-SSR
2️⃣ Install Dependencies

bash
Copy
Edit
npm install
3️⃣ Setup Environment Variables
Create a .env file and add:

ini
Copy
Edit
PORT=3000
MONGODB_URI=your-mongodb-connection-string
4️⃣ Run the Server

bash
Copy
Edit
npm start
5️⃣ Open in Browser

arduino
Copy
Edit
http://localhost:3000
