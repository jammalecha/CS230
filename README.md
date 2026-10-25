# CS230

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

   The Gaming Room was a client looking to expand their existing Android game, Draw It or Lose It, to support multiple operating platforms. They wanted a web-based application that could support multiple teams and players in a game session. The application needed to manage game sessions, prevent duplicate game names, and provide a consistent experience across different devices and operating systems.

2. What did you do particularly well in developing this documentation?

   I think I did particularly well in evaluating the different operating platforms and recommending Linux as the server operating system. I considered factors such as scalability, cost, memory management, storage, and security. I also provided recommendations for using MySQL to manage structured game data and separating image assets from the database. These recommendations helped support the application's requirements while considering its future growth.

3. What about the process of working through a design document did you find helpful when developing the code?

   Working through the design document helped me better understand the application's requirements before beginning development. Identifying the different componets and how they interact made it easier to understand how the application should be structured. Creating the domain model was particularly helpful because it showed the relationships between games, teams, and players, which could then be implemented using object-oriented programming principles such as inheritance.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

   If I could revise on part of my documentation, I would expand the memory management section to better explain how Java manages memory within the application. While I discussed Linux virtual memory, swapping, and loading images when needed, I could have included more information about the JVM's garbage collector and heap memory configuration. This would provide a better explanation of how Java and Linux work together to manage memory during periods of high player activity. (made these corrections in the currently uploaded document)

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

   I interpreted the client's needs by identifying the application's requirements and considering how they would affect the overall design. Since The Gaming Room wanted the game to work across multiple operating platforms, I recommended we use a web-based client-server architecture with Linux as the server operating system. I also considered scalability, security, and maintaining game sessions when players temporarily disconnect. Considering the user's needs is important because the software needs to meet their expectations while remaining reliable and efficient.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

   I approached the software design by first reviewing the client's requirements and identifying the application's main components. From there, I evaluated different operating systems and considered their advantages and disadvantages before making my recommendations. I also used object-oriented design principles and a UML domain model to help organize the application. In future projects, I would continue breaking down the requirements, comparing possible solutions, and documenting design decisions before beginning development.
