# ITI_Graduation_project-

Examination System
The Examination System is a comprehensive platform designed to streamline the process of managing students, courses, instructors, and examinations. This project was developed from scratch by our team to cover the full life cycle of a digital exam management system, from backend database management to a user-facing web interface.
________________________________________
 Project Overview
The Examination System includes:
•	A SQL Server database to manage:
o	Students
o	Courses
o	Instructors
o	Exams and exam results
•	A set of stored procedures to handle all CRUD operations (Create, Read, Update, Delete) for each database table.
•	A dataset of over 8,000 records populated to simulate a real-world educational environment.
•	SSRS reports for generating insightful printable reports and summaries.
•	20 Power BI dashboards for in-depth analysis and visualization of student performance, course statistics, and instructor activities.
•	A Streamlit web application that allows:
o	Instructors to create exams
o	Students to log in, take exams, and view results instantly
o	Role-based access control to ensure secure and personalized user experiences
________________________________________
 Features
•	Relational Database Design: Normalized schema ensuring efficient data integrity and scalability.
•	Stored Procedures: Modular procedures for inserting, deleting, and updating records in all tables.
•	Data Visualization:
o	Power BI dashboards for KPIs and insights
o	SSRS reports for administrative use
•	Web Interface (Streamlit):
•	This project is a web-based Examination System developed using Streamlit, designed to manage student exams and instructor analytics. It connects to a Microsoft SQL Server database and provides a simple, role-based interface for both students and instructors.
•	Features 
 Role-based login (Student or Instructor)
  Instructors can:
      Log in using their ID
      Create exams via the [GenerateExam] stored procedure
  Students can:
       Log in using their ID
      Take exams assigned to them
      Submit answers via the [StudentAnswers] procedure
      View results immediately after completion (via [CorrectExam])
     Clean and intuitive UI matching the design spec
•	Exam Correction Logic:
o	Auto-correction of submitted answers via stored procedures
o	Real-time feedback for students
________________________________________
 Technologies Used
•	Database: Microsoft SQL Server
•	Reporting: SSRS
•	Visualization: Power BI
•	Web Framework: Streamlit (Python)

