🏥 Hospital Management Information System (HMIS)

 📌 Project Overview
The Hospital Management Information System (HMIS) is a web-based application developed to digitalize hospital operations including patient management, medical records, discharge processing, and inventory control.

The system replaces manual record-keeping with a structured, secure, and database-driven solution.


 🚀 Key Features
- Secure Login & Role-Based Access Control (RBAC)
- Patient Registration & Unique MR Code Generation
- Patient Visit History Tracking
- Medical Records Management
- Discharge Summary Generation
- Inventory Management (Purchase Order & GRN)
- Automated Stock Updates



 🧱 System Architecture
The system follows a 3-tier architecture:

- **Presentation Layer:** Oracle APEX
- **Application Logic:** PL/SQL
- **Database Layer:** Oracle Database



🛠 Tech Stack
- Oracle APEX
- Oracle Database
- SQL
- PL/SQL



 🗄 Database Design
The database includes the following main tables:

- PATIENT
- VISIT
- MEDICAL_RECORD
- DISCHARGE
- ITEM
- PO_HEADER
- GRN_HEADER
- USER
- ROLE

Refer to the ERD diagram below:

![ERD](HMIS_ERD.png)


 🔐 Security Implementation
- Role-Based Access Control (RBAC)
- Authentication & Authorization
- Controlled module access per user role



 🧪 Testing
- Unit Testing of individual modules
- Integration Testing
- Validation of stock update logic
- Role permission testing



 📈 Future Improvements
- Billing & Payment Module
- Pharmacy Integration
- Lab Integration
- Dashboard Analytics



 👤 Author
**Abdullah Iftikhar
Computer Science Undergraduate  
Interested in Cyber Security & Software Quality Assurance
