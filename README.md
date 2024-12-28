# Deadline Reminder for Remote Teams

## Project Description
**Deadline Reminder for Remote Teams** is a simple MicroSaaS application designed to help remote teams keep track of task deadlines in different time zones. It fetches task deadlines from a database, converts them to the local time of the assigned team member, and sends personalized reminders. This tool solves the challenge of managing deadlines across distributed teams by automatically handling time zone conversions.

The project is practical and feasible for a one-person startup, targeting small remote teams or freelance groups.

---

## Features Overview
- **Task Management**:
  - Store and manage tasks with details like task name, due date, assigned user, and timezone.
- **Automatic Time Zone Conversion**:
  - Convert UTC deadlines to the local time of the assigned user.
- **Personalized Reminders**:
  - Generate user-specific reminders with task details and local due times.
- **Database Integration**:
  - Persistent storage of tasks using a relational database (H2 for prototyping, MySQL for production).


> **Note**: This is a prototype. The features listed above are not fully implemented in this version but can be expanded upon in the future.

---

## Setup Instructions

### Prerequisites
- **Java Development Kit (JDK)**: Version 17 or higher.
- **Maven**: Build tool to manage dependencies.
- **Database**: H2 (in-memory) or MySQL for persistent storage.

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/deadline-reminder.git
   cd deadline-reminder
2. Open the folder in intelliJ or any other IDE of your choice and run the following file: "remotedeadline\src\main\java\com\example\reminder\remotedeadline\RemotedeadlineApplication.java"  
   Now the app will be up and running then access the below endpoint for reminders  
To fetch reminders: http://localhost:8080/api/reminders  

## Future Enhancements
1. Integrate email or Slack notifications for reminders.  
2. Add a user-friendly frontend using React or Angular.  
3. Enable authentication for secure access to task data.  

