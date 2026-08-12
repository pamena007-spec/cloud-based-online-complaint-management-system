# Cloud-Based Online Complaint Management System

## 📌 About the Project

The Cloud-Based Online Complaint Management System is a cloud computing project that allows users to submit complaints online. The complaint information is stored in a cloud database using Supabase.

The project demonstrates how cloud computing can be used for centralized data storage and online complaint management.

## 🎯 Objectives

- To provide an online platform for submitting complaints.
- To store complaint data in the cloud.
- To reduce manual complaint management.
- To demonstrate the practical use of cloud computing.

## 🛠️ Technologies Used

- Python
- Flask
- Supabase
- Google Colab
- HTML
- CSS
- ngrok

## ☁️ Cloud Technology

Supabase is used as the cloud database to store and manage complaint information.

### Architecture

User
  ↓
Flask Application
  ↓
Supabase Cloud Database

## ✨ Features

- Submit complaints online
- Store user name and email
- Store complaint details
- Store data in a cloud database
- View submitted complaints
- Track complaint status

## 🗄️ Database

The project uses a Supabase table named `complaints`.

| Field | Description |
|---|---|
| id | Unique complaint ID |
| name | User name |
| email | User email |
| complaint | Complaint description |
| status | Complaint status |
| created_at | Date and time |

## 🚀 How to Run

1. Open the project notebook in Google Colab.
2. Install the required Python packages.
3. Connect the application to Supabase.
4. Configure the Supabase cloud database.
5. Run the Flask application.
6. Start ngrok to create a public URL.
7. Open the generated URL in a browser.
8. Submit a complaint.
9. Check the submitted complaint in the Supabase cloud database.

## 🔐 Security

Do not upload your Supabase API key or ngrok authentication token to GitHub.

Use placeholders such as:

```python
SUPABASE_URL = "YOUR_SUPABASE_URL"
SUPABASE_KEY = "YOUR_SUPABASE_KEY"
