# The-Gaming-Room
The Gaming Room wants a web-based game called “Draw It or Lose It” that can be used on multiple platforms.

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

Our client was The Gaming Room, a company which developes games. The type of software they wanted us to design was a web-based application that can be available on multiple platforms. Technical requirements for this application include:
•	Singleton pattern so that there is only one instance of the game in memory at any given time.
•	The game can have multiple teams.
•	The game can have multiple players.
•	Games and team names need to have unique identifiers.
•	The game will have four rounds, each lasting one minute each. 
•	The image displayed in the game should slowly render, being fully revealed by 30 seconds. 
•	The other team has 15 seconds to guess the photo if the first team fails. 
•	The system needs to support loading and rendering from a large stock drawing library with timed visibility mechanics. 
•	The program must be built with web compatible software.

What did you do particularly well in developing this documentation?

I was able to use the UML diagram to make a list of software requirements that would meet the clients needs. I was also able to use resources to adequately explain how we can meet the necessary software requirements. 

What about the process of working through a design document did you find helpful when developing the code?

Going through the design document helped me a lot because it gave me a clear outline before I started coding. Instead of guessing what to do next, I already had the requirements laid out and could focus on turning them into code. It made the process less overwhelming since I could just follow the plan step by step.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could go back and change one part, I’d spend more time on showing how the classes connect, like the game, teams, and players. I think making a stronger diagram or adding examples would have helped me see the “big picture” better and probably made writing the code even easier.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I looked at what the client wanted most, like making sure team names are unique, allowing multiple teams, and only having one game running at a time. I added things like unique identifiers to meet those needs. Thinking about what the user wants is super important because if the software doesn’t actually work the way they expect, then it’s not really useful to them.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach was to break everything into smaller pieces, like focusing on the game, then teams, then players. Using object-oriented design helped me keep things organized. In the future, I’d use diagrams earlier on and maybe write out user stories to keep track of how the program is supposed to work. I’d also try to get feedback sooner, so I know I’m on the right track before spending too much time coding.
