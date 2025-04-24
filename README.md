# 🦷 Tooth-Tale Checkup System

A full-stack web application built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js) that simulates a basic **dental checkup system** for both patients and dentists. This project demonstrates full-stack development, file handling, user roles, and PDF export functionality.

---

## 📌 Objective

Develop a user-friendly application that allows:
- **Patients** to request dental checkups from registered dentists.
- **Dentists** to upload images and notes from checkups.
- **PDF export** of checkup reports for the patients.

---

## 💻 Tech Stack

### Frontend
- **React.js**
- Tailwind CSS or Material-UI 

### Backend
- **Node.js** + **Express.js**
- **MongoDB** (Local or MongoDB Atlas)
- **Mongoose** for object modeling
- **supabase**
- **Multer** for image uploads
- **jsPDF** or **html2pdf.js** for PDF generation

---

## 🧑‍⚕️ User Roles & Features

### 👤 Patient (User)
- Register/Login (Optional but recommended)
- View available dentists (fetched from MongoDB)
- Select a dentist and request a checkup
- View uploaded checkup results (images + notes)
- Export checkup report as a **PDF**

### 🧑‍🔬 Dentist
- Register/Login (Optional but recommended)
- View list of checkup requests from patients
- Upload one or more images related to the checkup
- Add a description or note for each image
- Save this data to MongoDB for patient access




