# 📧 BulkMail – Send Emails in Bulk
BulkMail is a full-stack project that allows you to send emails to multiple recipients at once using **React** for the frontend, **Express + Node.js** for the backend, and **MongoDB** for storing Gmail credentials.  
It uses **Nodemailer** to handle email delivery and supports uploading recipient lists from Excel/CSV files.

---

## 🚀 Features
- Upload an Excel/CSV file containing email addresses.
- Compose and send a custom message to all uploaded emails.
- Gmail credentials securely stored in MongoDB.
- Progress/status indicator during sending.
- Simple and responsive UI built with TailwindCSS.

---

## 🛠 Tech Stack
- **Frontend:** React, TailwindCSS, Axios, XLSX.js
- **Backend:** Node.js, Express.js, Nodemailer
- **Database:** MongoDB (Mongoose ODM)

---

🔗 Live Website
👉 https://bulkmail-1-5ro0.onrender.com/

---

## 📂 Project Structure
BulkMail/
│
├── backend/ # Express server
│ ├── index.js # Main backend entry
│ └── package.json
│
├── frontend/bulkmail/ # React app 
│ ├── src/
│ │ ├── App.js # Main UI
│ │ └── index.css
│ └── package.json
│
└── README.md # Project documentation
