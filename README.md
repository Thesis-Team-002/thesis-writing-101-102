# Web-Based Disaster Relief Assistance and Monitoring System for Affected Communities 


This project aims to develop a centralized system for disaster relief management that enhances coordination, transparency, and efficiency during relief operations. The system provides a unified platform for monitoring, recording, and managing disaster-related information to ensure that assistance is delivered accurately and on time.

## Features
- **Monitoring and Reporting** - The system shows updates on relief operations.
Admins can see which areas have received help.
- **Track Donations and Relief Distribution** - The system records and monitors all donations and relief goods.
It keeps track of what is received and where it is delivered,
making the process organized, fair, and transparent.
- **List of the affected families and their needs** - Shows a list of the affected families and what they need.  
- **Notification and Alert System** - The system can send alerts or notifications to users and administrators regarding new disaster events, donation updates, or urgent relief needs. This feature helps improve communication and ensures timely responses during emergencies.
- **User Management and Access Control** - This feature allows the system administrator to manage user accounts and assign specific roles such as admin, staff, or volunteer. It ensures that only authorized personnel can access and modify sensitive data, maintaining system security and data integrity.
- **Search and Filter Function** - Lets users quickly search for affected families, donations, or areas using keywords or filters (like location or status).

  ## Installation Steps
1. Clone the Repository
```bash
git clone https://github.com/yourusername/d-r-system.git
cd disaster-relief-system
```
2. Backend Setup ( Express + Node.js + MySQL)
```bash
cd backend
npm install
```
Create a .env file inside the backend folder and add your configuration:
```bash
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=disaster_relief_db
PORT=5000
```
Run the backend server:
```bash
npm run dev
```
By default, it runs at http://localhost:5000
3. Frontend Setup (React.js + Vite)
```bash
cd ../frontend
npm install
```
Create a .env file inside the frontend folder:
```bash
VITE_API_URL=http://localhost:5000
```
Run the frontend:
```bash
npm run dev
```
4. Access the System
Open your browser and go to:
http://localhost:5173
5. Installation Note
```bash
At this stage, the installation process for the system is not yet applicable, as the project is still in its development phase. 
There are currently no available setup files, resources, or localhost configurations to demonstrate the installation. 

Once the system is completed, this section will be updated to include detailed installation procedures, 
such as cloning the repository, configuring the database, and running the system on a local server. 
This serves as a placeholder for future documentation when the system becomes fully functional.
```
## Screenshot
(https://github.com/user-attachments/assets/46311d9c-a7a3-4d5e-8993-d49e19fc4182) 

## Academic Context:
This project is developed by 4th-year Computer Science students of Mabini Colleges, Inc., as a fulfillment of the academic rrequirements in THS 101 (Thesis Writing 101).

*Leader*
- Jhon Loyd E. Canaria

*Members*
- Angelica Jane A. De Vera 
- Darene Kinda E. Bamba
- Hazel Talibong
- Christol Joy Rellora
- Kristina Mhae Salenga
