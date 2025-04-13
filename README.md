# ERP-Master

**PROJECT OVERVIEW**

The College ERP (Enterprise Resource Planning) project is a web-based management system developed to streamline and automate the administrative tasks of a college or educational institution. The system is primarily built using Django (Python framework) and supports different user roles such as Admin, Student, and Staff.

It aims to manage:
- Student details
- Staff information
- Attendance tracking
- Leave applications
- Notifications
- Feedback mechanisms

This system is useful for institutions looking to maintain records and communication efficiently through a centralized platform.

**Tools Used**

- Backend: Python, Django
- Frontend: HTML, CSS, Bootstrap
- Database: SQLite (default Django database)
- Other Tools: Django Admin panel for management, Bootstrap for UI components

**Data Exploration Steps**

Django admin interface and web views have been used to interact with the data:

- User Creation: Admin can add students, staff, and other users.
- Attendance Data: Staff can take and update student attendance.
- Leave Applications: Staff and students can submit leave requests.
- Feedback & Notifications: Users can post feedback and receive system messages.

**Key Features & Insights**

- Role-Based Access: The system separates views and actions for Admin, Staff, and Student.
- Attendance Management: Easy interface for marking and reviewing attendance.
- Feedback Module: Simple way for students to submit feedback to admins.
- Leave Handling: Streamlined process for staff leave application and approval.
- Custom Dashboards: Each user role has a dashboard with relevant metrics and options.
