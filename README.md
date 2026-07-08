UET Digital Management System (UDMS)
https://img.shields.io/badge/platform-Web-blue
https://img.shields.io/badge/license-MIT-green

UDMS is a comprehensive web‑based university management system that digitizes academic, administrative, and campus‑wide operations. It integrates biometric attendance, course registration, fee management, leave tracking, society management, timetables, emergency notifications, and classroom availability into a single, role‑based platform. Built with a modern web stack (HTML, CSS, JavaScript, C# backend) and a relational database, UDMS streamlines workflows for students, teachers, administrators, society heads, and staff—reducing manual effort and improving transparency across the university.

🚀 Key Features
General System (No Login Required)
Biometric Attendance – Fingerprint‑based verification with live status feedback.

View Timetable – Searchable schedules for students and teachers.

View Free Classrooms – Real‑time room availability for makeup lectures or study.

Emergency Notifications – Scrollable alerts for urgent announcements (visible without login).

Campus Map – Interactive navigation with classroom search.

View Events – List of upcoming university events and details.

Role‑Based Specialized Modules
Role	Core Functionalities
Student	Course registration, fee challan (view/pay), DMC & results, attendance analysis (graphs), leave application, society registration, teacher meeting requests, feedback surveys, notifications.
Teacher	Mark class attendance (manual/bulk), upload DMC/marks, approve student meetings, view own attendance & salary status, apply leave, generate notifications, cancel classes.
Admin	User registration, timetable generation, fee challan creation & verification, attendance monitoring & warnings, leave approvals, society management, emergency broadcasts, survey analysis.
Society Head	Create/update societies, manage membership requests, assign tasks, schedule meetings/events, notify members.
Staff	View assigned tasks, update completion status, assist in society operations, view meetings/events.
🛠️ Technologies & Tools
Technology	Purpose
HTML / CSS / JavaScript	Frontend user interface
C# (ASP.NET / .NET)	Backend logic & API handling
Relational DBMS (SQL Server / MySQL)	Persistent data storage
Biometric Fingerprint Device	Hardware integration for attendance
UBL Bank API (simulated)	Fee payment verification
Notification System	Email / in‑app alerts
Git / GitHub	Version control & collaboration
📂 Project Structure
text
UDMS/
├── src/                # All source code (frontend, backend)
├── docs/               # SRE documentation, wireframes, use cases, diagrams
├── data/               # Database scripts / sample data (optional)
├── README.md
├── LICENSE
└── ...
👨‍💻 Team & Development
Dua Ahmed – Admin & Society modules, Wireframes, RTM

Arooj Rafique – Student & Teacher modules, Use Cases, SRE assembly

Fizza Naeem – General system, Staff module, GANTT, User Stories

Methodology: Agile – iterative development with continuous feedback from stakeholder simulations.

🏁 How to Run
Clone the repository:
git clone https://github.com/your-username/udms.git

Open the solution in your preferred IDE (Visual Studio, etc.).

Configure the database connection string in appsettings.json (or equivalent).

Build and run the project.

Access the application via http://localhost:port and log in with pre‑seeded credentials (or use the admin registration).

Note: Ensure the biometric device drivers are installed if using hardware attendance.

🔮 Future Work
Upgrade to cloud‑hosted deployment (Azure / AWS).

Integrate real‑time payment gateways (Stripe, Easypaisa).

Add mobile app (iOS/Android) for students and teachers.

Implement AI‑based analytics for attendance and performance prediction.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

📬 Contact
For questions or collaboration, please open an issue or reach out to the team via GitHub Issues.
