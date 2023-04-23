# CS 230 Module 8 Journal

**Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**

The client is The Gaming Room, and they have hired Creative Technology Solutions (CTS) to develop a web-based version of their current Android app game called "Draw It or Lose It". The game is based on the classic Win, Lose or Draw concept where teams compete to guess what is being drawn. The software should be web-based and have multi-team and multi-player functionality, unique game and team names, and unique identifiers for each instance of a game, team, or player to ensure that only one instance of the game can exist in memory at any given time. 

**What did you do particularly well in developing this documentation?**

In developing this documentation, I was able to clearly articulate the requirements, design constraints, system architecture, and domain model for the Draw It or Lose It project. I also provided a thorough evaluation of the characteristics, advantages and weaknesses of different operating platforms and development tools. I also was able to made recommendations for various system architectures and techniques specific to distributed systems, storage management, memory management, and security. 

**What about the process of working through a design document did you find helpful when developing the code?**

The document can help to establish the requirements and constraints for the project, define the architecture and components of the system, and provide a clear understanding of how the different parts of the project should work together. This can help to ensure that the development process is organized and efficient and also can prevent issues and errors that may arise from a lack of planning. Furthermore, having a clear design document can make it simpler for developers to interact with stakeholders and with one another because everyone will be on the same page on what needs to be done and how it will be done.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**

If I could revise one part of this document, I would improve the Domain Model section by adding more details about the relationships between classes, particularly the one-to-many associations. Specifically, I would update the Game, GameService, Team and Player classes to have a zero to many association instead of one to many, as this better reflects the requirements for the game. Additionally, I would provide more information about the attributes and methods of each class, as well as include examples to illustrate how the classes are used in the game. This would improve implementation efficiency and effectiveness since the development team would have a better knowledge of how the domain model translates into the actual code.

**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**


