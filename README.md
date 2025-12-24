# Student Record Database Management System (Architecture)

### 📋 Overview
This project was designed to automate student record-keeping for administrative efficiency. It focuses on maintaining high data integrity and optimizing retrieval speeds for large datasets using a relational database approach.

### 🛠️ Tech Stack
* **Language:** Python
* **Database:** MySQL
* **Tools:** MySQL Workbench, PyCharm

### 🏗️ Database Architecture
The system utilizes a relational schema designed in **3rd Normal Form (3NF)** to reduce data redundancy.

**Key Tables & Relationships:**
* `Students`: Primary Key (`student_id`), Name, Email, Enrollment Date.
* `Courses`: Primary Key (`course_id`), Course Name, Credits.
* `Enrollments`: Foreign Keys linking `student_id` and `course_id`.
* **Constraints:** Implemented `ON DELETE CASCADE` and `FOREIGN KEY` constraints to ensure referential integrity.

### 🚀 Key Features & Logic
* **Data Consistency:** Utilized ACID properties to ensure reliable transaction processing.
* **Complex Queries:** Developed optimized SQL joins to generate student transcripts and course rosters.
* **Error Handling:** Integrated Python try-except blocks to manage database connection timeouts and duplicate entry errors.

### 🧪 Quality Assurance
* **Testing:** Conceptualized unit tests to validate data input formats before database insertion.
* **Validation:** Ensured no null values in critical fields like IDs and contact information.

---
*Note: This repository serves as a technical documentation of the system's architecture and design logic.*
