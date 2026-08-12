Cloud-Based Online Complaint Management System
📌 Project Description

The Cloud-Based Online Complaint Management System is a cloud computing project designed to provide an easy and efficient way for users to submit and manage complaints online.

The application uses Python Flask for the application layer and Supabase as the cloud database. Complaint details are stored in the cloud, allowing centralized and easy data management.

🎯 Objectives
To provide an online platform for submitting complaints.
To store complaint data in a cloud database.
To reduce manual complaint management.
To demonstrate the use of cloud computing in a real-world application.
🛠️ Technologies Used
Python
Flask
Supabase Cloud Database
Google Colab
HTML
CSS
ngrok
☁️ Cloud Computing

Supabase is used as the cloud database for storing complaint information.

System Architecture
User
  ↓
Flask Application
  ↓
Supabase Cloud Database
✨ Features
📝 Submit complaints
👤 Enter user details
📧 Store email information
☁️ Store complaints in the cloud
📋 View submitted complaints
🔄 Track complaint status
🗄️ Database Structure

The project uses a Supabase table named complaints.

Field	Description
id	Unique complaint ID
name	User name
email	User email
complaint	Complaint description
status	Complaint status
created_at	Date and time of complaint
🚀 How to Run
Open the project in Google Colab.
Install the required Python packages.
Configure the Supabase Project URL and API key.
Connect the Flask application to Supabase.
Run the Flask application.
Configure ngrok authentication.
Start the ngrok tunnel.
Open the generated public URL.
Submit a complaint.
Verify the complaint in the Supabase cloud database.
🔐 Security

API keys and ngrok authentication tokens should not be uploaded to GitHub.

Use placeholders in the public project code, for example:

SUPABASE_URL = "YOUR_SUPABASE_URL"
SUPABASE_KEY = "YOUR_SUPABASE_KEY"
✅ Advantages
Cloud-based storage
Easy to use
Centralized complaint management
Accessible through the internet
Reduces paperwork
Easy to maintain and update
🔮 Future Enhancements
Admin login
Complaint search and filtering
Email notifications
Complaint status updates
Admin dashboard
User authentication
🏁 Conclusion

The Cloud-Based Online Complaint Management System demonstrates the practical use of cloud computing for complaint management. By combining Flask with the Supabase cloud database, complaint information can be submitted, stored, and managed efficiently using cloud technology.
