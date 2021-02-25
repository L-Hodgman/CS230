# CS230
SNHU CS230

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
  The Gaming Room was a game development company that wanted to create a web-based version of their game Draw It or Lose It. Their requirments included that each game had to have one or more teams playing. Each team had to have multiple players. Each player and team had to have unique names to be able check if they were already in use. Lastly, only one game intance could exist in memory at any given time.

What did you do particularly well in developing this documentation?
  I explained with simplicity and clarity what the client wanted for the Executive Summary. Also, I put a lot of thought and research into the Software Development Requirements. I tried to simplify the pros and cons for the server platforms, server clients, and development tools.

What about the process of working through a design document did you find helpful when developing the code?
  When looking at the domain model, it allowed me to know what classes, methods, and variables would be needed. The model also visualized the type of relationship between the classes. 

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  I would want to revise the development tools part of the Development Requirements. I would want to research more into tools that could be used for development on each platform. I found it difficult to take the time to understand exactly what the tools did.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  Since the user wanted only one instance of a game in memory, we used a singlton pattern. Also, the client wanted unique names and identifiers of a game, team, and player. To accomplish this need, we used an interator to see if the name already existed. It is important to consider the user's needs when designing to know what type of patterns to use within the code.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
  I looked at what the client wanted in the software because it allowed me to think about what to include in the code. Afterwards, creating and using a UML template was very useful in visualizing the structure of the code. A UML will be something that I will use in future designs to model an application.
