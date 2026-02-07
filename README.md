CLINIC-MANAGEMENT-SYSTEM
### Admin Dashboard
![Admin Dashboard](https://geynesis.com/wp-content/uploads/2024/03/Hospital.jpg)

(ASP.NET Web Application)

📄 Description

CLINIC-MANAGEMENT-SYSTEM is a web-based healthcare management system developed using C# ASP.NET, designed to support clinic administrative operations and patient communication. The system focuses on efficient clinic management through an Admin-controlled dashboard and automated patient notifications via SMS (text-only) and Email.

It aims to improve appointment coordination, patient record handling, and communication efficiency while reducing manual processes. This project is suitable for real-world clinic workflow simulation, academic use, and professional portfolio presentation.

🚀 Features
🏥 Clinic Administration

Admin dashboard for clinic operations

Patient record management

Appointment scheduling and monitoring

Clinic staff account management

📅 Appointment Management

Patient appointment booking

Appointment status tracking

Schedule conflict prevention

Appointment reminders

📩 Patient Notifications

SMS (text-only) notifications

Appointment reminders

Status updates

Email notifications

Appointment confirmations

Clinic announcements

Follow-up reminders

👥 User & Access Control

Secure authentication

Role-based access (Admin, Staff)

User account and permission management

🛠️ Tech Stack

Backend: C# ASP.NET (MVC / Core)

Frontend: Razor Pages / Bootstrap

Database: SQL Server

SMS Integration: SMS Gateway API (text-only)

Email Service: SMTP (Gmail / Outlook / Custom)

Authentication: ASP.NET Identity

Server: IIS

📂 Project Structure
├── Controllers/
├── Models/
├── Views/
├── Data/
├── Services/
├── wwwroot/
│   ├── css/
│   └── js/
├── appsettings.json
├── Program.cs
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/CLINIC-MANAGEMENT-SYSTEM.git
cd CLINIC-MANAGEMENT-SYSTEM

2️⃣ Open the project

Open the solution in Visual Studio

Restore NuGet packages if prompted

3️⃣ Configure database

Update appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=ClinicManagementDB;Trusted_Connection=True;"
}

4️⃣ Apply migrations
Update-Database

5️⃣ Run the application

Press F5 or Ctrl + F5

Access via:

https://localhost:5001

📩 SMS & Email Configuration
SMS (Text Only)

Configure SMS gateway API credentials

Supports appointment reminders and alerts

Text-only messaging for reliability

Email

SMTP configuration via appsettings.json

Automated email notifications for patients

🔐 User Roles

Admin – Full system control and configuration

Staff – Appointment and patient management

🧪 Testing

Manual UI testing

Validation testing for appointments and notifications

📈 Future Enhancements

Patient portal access

Online appointment booking

Medical history records

Multi-clinic support

Mobile app integration

Reporting and analytics dashboard

🤝 Contribution

Contributions are welcome!

Fork the repository

Create a new feature branch

Commit your changes

Submit a pull request

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Kee Ken
ASP.NET & Laravel Developer
📍 Philippines
