## FADDS: A Web-Based Data-Driven Decision Support System for Equitable Distribution of Government Assistance

This project aims to develop a web-based Fair Aid Distribution and Documentation System (FADDS) that supports barangay officials in managing and distributing government assistance in a more transparent, organized, and data-driven manner.

The system provides a centralized platform for recording beneficiary information, analyzing socio-economic data, and prioritizing beneficiaries through an automated ranking process. By replacing manual and paper-based processes, the system helps reduce errors, minimize bias in beneficiary selection, and improve the efficiency and fairness of government assistance distribution.

FADDS is designed to support barangay-level operations by improving documentation, monitoring, and reporting of assistance programs while promoting transparency and accountability in local governance.

## Features

**Beneficiary Data Management** - The system provides a centralized database for storing and managing beneficiary information. Barangay officials can record, update, and maintain profiles of residents who may qualify for government assistance.

**Socio-Economic Data Encoding** - Barangay staff can encode relevant socio-economic information such as household size, employment status, income level, and housing conditions. This data serves as the basis for determining eligibility and prioritization of beneficiaries.

**Data-Driven Prioritization and Ranking** - The system automatically evaluates and ranks beneficiaries based on predefined socio-economic criteria. This feature helps ensure that assistance is distributed objectively and fairly, reducing reliance on subjective decision-making.

**Assistance Documentation and Tracking** - All government assistance records are stored and documented within the system. This allows barangay officials to track which beneficiaries received aid, what type of assistance was provided, and when the distribution occurred.

**Monitoring and Reporting** - The system provides reporting tools that allow administrators to generate summaries of beneficiaries, aid distribution, and assistance programs. These reports help improve transparency and support data-driven decision-making.

**Search and Filter Function** - Users can easily search and filter beneficiary records using keywords or categories such as name, location, or assistance status. This helps speed up data retrieval and improves system usability.

**User Management and Access Control** - The system administrator can manage user accounts and assign roles such as administrator or staff. This ensures that only authorized users can access or modify sensitive data within the system.

 ## Installation Steps
1. Clone the Repository
```bash
git clone https://github.com/angelicajanedevera-dot/d-r-system.git
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

6. Installation Note
```bash
At this stage, the installation process for the system is not yet applicable, as the project is still in its development phase. 
There are currently no available setup files, resources, or localhost configurations to demonstrate the installation. 

Once the system is completed, this section will be updated to include detailed installation procedures, 
such as cloning the repository, configuring the database, and running the system on a local server. 
This serves as a placeholder for future documentation when the system becomes fully functional.
```
## Screenshot
[Screenshot](https://github.com/user-attachments/assets/46311d9c-a7a3-4d5e-8993-d49e19fc4182) 

## Academic Context:
This project is developed by 4th-year Computer Science students of Mabini Colleges, Inc., as a fulfillment of the academic requirements in THS 101 (Thesis Writing 101). This project aims to develop an easy access web-based Disaster Relief Assistance and Monitoring System for Affected Communities. 

*Leader*
- Jhon Loyd E. Canaria

*Members*
- Angelica Jane A. De Vera 
- Darene Kinda E. Bamba
- Hazel Talibong
- Christol Joy Rellora
- Kristina Mhae Salenga
