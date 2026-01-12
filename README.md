# TrackIT
A real-time analytics tool to track website traffic using ASP.NET, SignalR, .NET Core Identity, MS SQL Server, JavaScript, jQuery

## Demo
https://github.com/user-attachments/assets/cc936424-db86-4fd0-bc20-dc981b31ea08

## Screens
![register]()

![login](https://github.com/user-attachments/assets/f63e7484-b40c-4aac-a92a-56ca583db1a5)

![dashboard](https://github.com/user-attachments/assets/92543ab8-5aeb-427e-a68b-8a4dc301254b)

![flows](https://github.com/user-attachments/assets/d573a113-69de-491f-aa55-116ef0a46e75)


# TrackIT – Real-Time Website Analytics Tool

TrackIT is a real-time web analytics platform that tracks and visualizes website visitor behavior, enabling administrators to monitor traffic, user activity, and engagement metrics live.

---

## Overview

TrackIT is a real-time analytics system designed to capture, process, and display website traffic and user behavior data.
The application provides live insights into active users, page visits, session duration, and interaction patterns using real-time communication.

This project was developed as a **Final Year Project** to demonstrate full-stack software engineering skills, real-time data handling, and scalable backend design.

---

## Tech Stack

### Backend

* ASP.NET Core
* SignalR (Real-time communication)
* .NET Core Identity (Authentication & Authorization)
* MS SQL Server
* Entity Framework Core

### Frontend

* JavaScript
* jQuery
* HTML5
* CSS3
* Bootstrap

### Tools & Others

* Visual Studio
* SQL Server Management Studio (SSMS)

---

## Key Features

* Real-time tracking of website visitors
* Live dashboard displaying active users
* Page-wise traffic monitoring
* Session tracking and duration analysis
* User authentication and role-based access (Admin)
* Secure login using .NET Core Identity
* Real-time updates using SignalR without page refresh
* Persistent data storage using MS SQL Server

---

## System Architecture

The system follows a **layered architecture** with real-time event-driven communication.

**Architecture Components:**

* Presentation Layer (Dashboard UI)
* Application Layer (Business Logic)
* Data Access Layer (Entity Framework Core)
* Real-Time Communication Layer (SignalR Hub)

📌 **Add Architecture Diagram Here**
`/docs/architecture-diagram.png`

---

## Data Flow Overview

1. User visits a website integrated with TrackIT script
2. Visitor activity is captured via JavaScript
3. Data is sent to the backend API
4. SignalR broadcasts updates to the admin dashboard
5. Data is stored in MS SQL Server for analytics

📌 **Add Data Flow Diagram Here**
`/docs/data-flow-diagram.png`

---

## Screenshots

📌 **Add UI Screenshots Here**

* Admin Dashboard
* Live Visitors View
* Traffic Analytics View
* Authentication Pages

Example:

<table> 
  <tr>
    <td> <h2>Sign Up/h2> </td>
    <td> <h2>Sign In</h2> </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/7356e5e3-6bec-4e64-ab0e-ab0e50d8b40f.png">
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/79749919/234851500-f795bb2e-e243-4e6c-8775-6279dc1ab58a.png">
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/79749919/234852317-478fde7d-e990-474e-b3d3-81db0c91f5cf.png">
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/79749919/234852407-ec7d041e-c732-4570-99a2-17c875b44a7e.png">
    </td>
  </tr>

---

## Demo Video

🎥 **Project Demo Video**
*Add your demo video link here (YouTube / Google Drive / GitHub Releases)*

```
https://your-demo-video-link
```

---

## Authentication & Security

* Implemented authentication using **.NET Core Identity**
* Secure password hashing and user management
* Role-based access for admin dashboard
* Session-based access control

---

## Real-Time Communication

* SignalR hubs used to push real-time updates
* Live visitor count and page views updated instantly
* Eliminates need for page refresh or polling

---

## Database Design

* Relational database design using MS SQL Server
* Normalized tables for:

  * Users
  * Sessions
  * Page Visits
  * Activity Logs

📌 **Add ER Diagram Here**
`/docs/database-diagram.png`

---

## How to Run the Project

### Prerequisites

* .NET SDK
* MS SQL Server
* Visual Studio
* Browser (Chrome recommended)

### Steps

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/TrackIT.git
   ```

2. Configure database connection string in:

   ```
   appsettings.json
   ```

3. Apply migrations (if applicable)

   ```bash
   update-database
   ```

4. Run the application from Visual Studio
   or

   ```bash
   dotnet run
   ```

5. Access the application at:

   ```
   http://localhost:5000
   ```

---

## Testing

* Manual testing for real-time event accuracy
* Cross-browser testing
* Authentication and authorization testing
* Load testing with multiple concurrent users

---

## What I Learned

* Implementing real-time systems using SignalR
* Designing scalable web analytics solutions
* Secure authentication using .NET Core Identity
* Handling concurrent users and live data streams
* Structuring full-stack applications with clean architecture
* Working with relational databases in real-world scenarios

---

## Challenges Faced

* Managing real-time updates efficiently
* Synchronizing live data across multiple clients
* Optimizing database writes for high traffic
* Handling session tracking accurately

---

## Future Improvements

* Add heatmap-based analytics
* Export reports in CSV/PDF format
* Integrate charts using modern libraries
* Improve UI with modern frontend frameworks
* Add Docker support for deployment
* Deploy on cloud (Azure / AWS)

---

## Author

**Mahreen Asama**
Software Engineer
Java Spring Boot | ASP.NET Core
Aspiring Master’s student in Germany (2026)

---

