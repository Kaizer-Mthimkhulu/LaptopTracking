# LaptopTracking
📖 Project Overview
The Laptop Tracking System is a C# Windows Forms desktop application designed to manage, assign, and monitor laptops within an organization. It tracks assignment and return dates, and includes planned support for real-time location tracking via Firebase and Google Maps.

🛠️ Built With
Frontend: C# (Windows Forms)
Backend: SQL Server
Location Services (In Progress): Firebase + Google Maps API
🎯 Features
✅ Core Features
Add, edit, and delete laptops
Assign laptops to users
Track laptop return dates
View assignment logs
SQL Server database integration
🔔 Notifications (In Progress)
Return due reminders
Overdue alerts
🗺️ Location Tracking (Planned/In Progress)
Integration with Firebase
Google Maps-based visual location panel
Approximate geolocation via IP/Wi-Fi
📂 Database Schema Highlights
LaptopInfo Table
LaptopID
Brand
Model
SerialNumber
AssignedTo
AssignedDate
ReturnDate
AssignmentLog Table
LogID
LaptopID
UserID
AssignedDate
ReturnDate
📅 Development Timeline
Task 1
Core UI design
Add/edit/remove laptops
SQL connection + validation
Task 2
Assignment/return functionality
Assignment logging
Task 3
Notification system (in progress)
Return logic debugging
Task 4
Firebase integration started
Google Maps UI planned
🚀 Deployment
Currently deployed locally using Visual Studio and SQL Server

Planned deployment as MSI installer for organizational rollout

Firebase and Maps API integration requires internet access and secure configuration

🚀 Deployment

Currently deployed locally using Visual Studio and SQL Server

Planned deployment as MSI installer for organizational rollout

Firebase and Maps API integration requires internet access and secure configuration

SQL Server is currently hosted under Microsoft Azure's free tier, which may introduce security and reliability concerns for long-term use

🐞 Known Issues
Return logic may fail under certain conditions
Location accuracy limited due to reliance on GeoIP
Notifications may trigger incorrectly after return
🔮 Future Enhancements
Bulk import from Excel/CSV
Condition reporting at return
Full audit trail with timestamps
Improved UI with corporate-friendly design
Secure data transmission and encryption
🧭 System Workflow
Admin logs in
Adds/edits laptops
Assigns a laptop to a user
Tracks the device or returns it
Views logs and status updates
👤 Author
Developed by \Mindworx Academy


