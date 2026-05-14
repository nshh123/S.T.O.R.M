# Spatial Threat Observation & Rapid Mitigation (S.T.O.R.M)

## Project Overview
Spatial Threat Observation & Rapid Mitigation (S.T.O.R.M) is a database-driven system designed to monitor airspace activity using sensor data, detect potential threats, and trigger appropriate internal and public alerts. The project demonstrates advanced use of Oracle PL/SQL, including triggers, procedures, window functions, and bulk processing to support real-time threat analysis and response.

---

## Problem Statement
Modern airspace monitoring systems must handle large volumes of sensor data while quickly identifying and responding to potential threats. Manual analysis is slow and error-prone, especially when dealing with real-time events. This project addresses the need for an automated, reliable, and scalable database solution for threat detection and alerting.

---

## Key Objectives
- Design a normalized relational database for airspace threat monitoring  
- Capture and process real-time sensor data efficiently  
- Automatically classify threat levels using PL/SQL business logic  
- Trigger internal and public alerts based on detected threats  
- Demonstrate advanced SQL and PL/SQL features (cursors, bulk operations, window functions)

---

## Quick Start Instructions

### 1. **Clone the repository**
`git clone https://github.com/nshh123/Spatial-Threat-Observation-Rapid-Mitigation_S.T.O.R.M.git`
### 2. Open Oracle SQL Developer
- Connect using a user with privileges to create:
  - tables
  - sequences
  - triggers
  - procedures

### 3. Run database scripts
- Navigate to the `database/` folder
- Execute scripts in the following order:
  1. **Sequences**
  2. **Tables**
  3. **Functions**
  4. **Triggers**
  5. **Procedures**
  6. **Test data inserts**

### 4. Enable output for testing
`SET SERVEROUTPUT ON;`
### 5. Execute test procedures and queries
- Use the provided procedures to simulate:
  - **Sensor detections**
  - **Threat evaluation**
  - **Internal and public alert generation**

---

## 🔗 Project Documentation

Each major component of the project has its own `README.md` for detailed documentation:

- 📂 **ERD & Data Dictionary**  
  [see documentation](ERD&Data_Dictionary/README.md)

- 📂 **Database Configuration & Scripts**  
  [see documentation](database/README.md)

- 📂 **Audits & Restrictions (Triggers & Policies)**  
  [see documentation](<Audits & Restrictions/README.md>)

- 📂 **BPMN Diagrams & Process Flows**  
  [see documentation](BPMN/README.md)

- 📂 **DB Configuration Notes**  
  [see documentation](DB_Conf/README.md)

---

## Technologies Used

- **Oracle SQL & PL/SQL**
- **Triggers, Procedures, Functions**
- **Cursors & Bulk Processing**
- **Window Functions**
- **Git & GitHub** for version control

## License
This project is proprietary.  
Unauthorized use, reproduction, or distribution is strictly prohibited.

--- 

> All Implementations and analyses represent original work. No AI generated content was copied without attribution or adaptation.
