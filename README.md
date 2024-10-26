# CS-230 Software Design Document - The Gaming Room

# Summary

**Client:** The Gaming Room
  
**Application:** Draw It or Lose It
  
**Requirements:**  
    - Web-based environment  
		- Server-client architecture with real-time communication  
    - Support for multiple teams and players  
    - Stock images are rendered within 30 seconds  
    - Security and data integrity to prevent tampering and unauthorized access 
		
**Description:**  
>The Gaming Room wanted to develop a web-based application for their game "Draw It or Lose It." This game involves multiple teams and players interacting in real time, where players guess images that are drawn from a stock library of images (200 images, roughly 8MB in size). The client requested a system that supports multiple instances of the game, each with unique identifiers for games, teams, and players. 

# Evaluation
**What did you do particularly well in developing this documentation?**  
	
>One of the strengths I displayed while developing this documentation was the detailed breakdown of the design constraints, system architecture, and technical considerations, such as the need for unique identifiers and scalability. The analysis of various operating systems and platforms also provided a comprehensive understanding of how to implement the software across different environments. 

**What about the process of working through a design document did you find helpful when developing the code?**  

>The process of working through the design document was invaluable in structuring the software's overall architecture. The UML diagram was especially helpful in laying out the connections between classes and objects. This process also helped me identify key design patterns, like the Singleton pattern, and allowed me to work through critical aspects like security and memory management before writing any code. 

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**  

>If I were to revise one part of the document, it would be the "Evaluation" section concerning operating platforms. I would delve deeper into the trade-offs between different cloud hosting services and how they might impact long-term costs and scalability. This analysis would also include an evaluation of distinct memory storage services for long-term game data and statistics. By providing more detailed cost and performance analysis for cloud options like AWS, Google Cloud, and Azure, The Gaming Room could make more informed decisions regarding the deployment of their application as well as the potential for expansion within the context of a cloud-based environment. 

**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**

>I interpreted the client's needs by focusing on their primary goals of supporting multiple users in real time with seamless communication and a user-friendly interface. These were implemented into the software design by selecting a distributed system architecture and ensuring the application was scalable and secure. Considering the users' needs is crucial because it directly impacts the software's usability and performance. These factors directly impact long-term user retention and the potential monetization of the system.

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**

>My approach to designing the software involved understanding the system's requirements and then breaking down the design into manageable components using object-oriented principles and design patterns. In the future, I would use iterative design patterns with frequent feedback from stakeholders to ensure the software evolves with user needs. Additionally, I would incorporate more rapid prototyping to visualize and test features early in the design process. For this particular design, I would consider leaderboards and space for advertising. The leaderboard could assist with consistent user engagement and the banner space for advertisements could potentially offset operating costs. 
