# CS-230-Operating-Platforms
This repository contains my completed software design document for The Gaming Room project in CS 230: Operating Platforms.

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was the client for this project. They wanted to expand their Android game, Draw It or Lose It, into a web-based application that could work across multiple operating systems and devices. The application needed to support multiple games, teams, and players while making sure names and identifiers remained unique. The goal was to create a design that could support the game as it expanded beyond a single platform.

What did you do particularly well in developing this documentation?

I think I did particularly well at comparing the different operating platforms and making recommendations based on the actual needs of the application. Instead of choosing a platform simply because it could run the software, I considered factors such as cost, scalability, security, and how easily the application could support different types of users. This helped me recommend Linux as the server platform while still allowing players on Windows, macOS, Linux, Android, and iOS to access the game.

What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand how the different pieces of the application needed to work together before focusing on the code itself. The UML diagram was especially useful because it showed the relationships between GameService, Game, Team, Player, and Entity. Having that structure already planned made it easier to understand where information belonged and how the classes should interact when developing the application.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I were to revise one part of the document, I would expand the system architecture view. The project did not require that section to be completed, but after working through the rest of the design, I think a diagram showing the clients, web server, application, database, and network connections would make the overall design easier to understand. It would give both the client and development team a visual representation of how the major parts of the system communicate.

How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I interpreted the user's needs by looking at what the game needed to accomplish rather than focusing on a specific operating system. The Gaming Room wanted the game to reach users on different devices, so a web-based client-server design made more sense than developing a separate application for every platform. I also considered requirements such as unique game and team names, multiple players, security, and the ability to grow over time. Considering user needs is important because a technically functional application is not successful if it does not solve the problem the client actually has.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the design by first identifying the requirements and constraints and then breaking the application into smaller parts. I used object-oriented design, UML modeling, design patterns, and platform comparisons to determine how those parts should work together. In the future, I would use a similar process by defining the requirements first, identifying constraints, modeling the major components, and comparing possible technologies before making a final recommendation. This gives development a clear direction before too much time is invested in writing code.
