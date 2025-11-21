# 🎨 Draw It or Lose It  
*A Web-Based Game Application – SNHU CS-230 Project*  

---

## 🧩 Overview  
**Draw It or Lose It** is a **multi-user, web-based guessing game** inspired by the 1980s show *Win, Lose or Draw*.  
This project was created for **The Gaming Room**, a client who wanted to expand their existing Android-only version into a **distributed web application** that supports multiple users, teams, and rounds simultaneously.  

The game needed to be **scalable, secure, and accessible** across traditional operating systems (Windows, macOS, Linux) and mobile devices (Android and iOS).  
The web application was built using the **client-server architecture** and a **RESTful API** to manage user authentication, communication, and data flow efficiently.  

---

## ⚙️ Technologies Used  
- **Programming Language:** Java ☕  
- **Framework:** Dropwizard (for REST API development)  
- **Build Tool:** Maven  
- **Web Server:** Jetty (embedded in Dropwizard)  
- **Database (conceptual):** PostgreSQL and Redis  
- **Cloud Environment (recommended):** AWS or GCP using Linux (Ubuntu LTS)  
- **Version Control:** Git / GitHub  

---

## 🚀 Setup Instructions  

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/draw-it-or-lose-it.git
   cd draw-it-or-lose-it
Build the Project

bash
Copy code
mvn clean package
Run the Application

bash
Copy code
java -jar target/gameauth-1.0-SNAPSHOT.jar server config.yml
Access the App

Open your browser and visit: http://localhost:8080/gameusers

Log in with:

Username: user or admin

Password: password

🧠 Project Reflection
🏢 Client and Software Requirements
The client for this project was The Gaming Room, who wanted to expand their Android-based game Draw It or Lose It into a multi-platform web application.
The system needed to:

Support multiple concurrent games and players

Scale efficiently on web and mobile platforms

Include user authentication and secure data management
My role was to design and prototype the software architecture using a RESTful client-server model that could later be deployed to the cloud.

💪 What I Did Well
I did well documenting how each design choice connected to the client’s goals.
I focused on scalability, security, and cross-platform compatibility through the use of REST APIs, Dropwizard’s server framework, and user authentication.
The Evaluation and Recommendations sections of my documentation clearly outlined how Linux and cloud-based platforms offered the best balance between cost, performance, and flexibility.

🧾 What Helped During Development
Creating the design document first helped me understand how the system would work before coding.
By outlining server-side components, controllers, and API endpoints, I was able to structure the project logically and avoid unnecessary refactoring later.
This step also made debugging easier since each function had a clear purpose from the start.

🔁 What I Would Improve
If I could revise one part, I’d expand on distributed system design — especially in areas like load balancing, caching, and fault tolerance.
Adding examples of how services like AWS Elastic Load Balancer or CloudFront could improve uptime and performance would make the plan more realistic for production environments.
Including a visual diagram of the data flow between clients and servers would also help communicate the design better.

👥 Interpreting and Implementing User Needs
I interpreted the user’s needs by focusing on fast performance, easy access, and reliability.
The game’s users expect smooth gameplay and instant feedback, so I designed the system to load only necessary assets, manage memory efficiently, and protect user data through authentication.
Keeping the player’s experience in mind ensured that the design balanced both technical capability and usability.

🧩 Design Approach and Future Strategies
My approach was to build around modularity and scalability, using a client-server pattern where the backend and frontend could evolve separately.
Techniques like flowcharts, pseudocode, and defining REST endpoints helped me organize and visualize the project before coding.

In future projects, I would:

Use Agile methods with short iterations and feedback cycles

Implement Docker earlier for containerized development

Include automated tests for better stability before deployment

These strategies will help create more maintainable and cloud-ready software moving forward.

🌐 Additional Insights: Cloud vs. Traditional Platforms
While working on this project, I also learned how cloud environments change the way software is designed compared to traditional operating systems.
Instead of relying on a single server, applications in the cloud can scale horizontally across multiple nodes, making them more flexible and fault-tolerant.
Techniques like load balancing, auto-scaling, and serverless functions make cloud-based apps easier to maintain and more cost-efficient over time.

I found that designing Draw It or Lose It for cloud deployment encouraged me to think beyond just one environment — focusing instead on portability, scalability, and real-world performance.

🏁 Final Takeaway
Building Draw It or Lose It has given me hands-on experience with REST APIs, memory and storage management, and distributed system architecture.
Through this project, I learned how to take client requirements, document them clearly, and translate them into a working technical design that could scale and adapt across multiple platforms


*© 2025 Ashley Pleasant – Created for SNHU CS-230: Operating Platforms*
