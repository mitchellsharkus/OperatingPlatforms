# OperatingPlatforms
## The Gaming Room Software Design Project

### Project Overview

The Gaming Room was the client for this project. They had an existing Android game called Draw It or Lose It and wanted to expand it so people could play on different operating systems and devices. The game involves teams guessing images as they are drawn on the screen. They needed the application to support multiple games, teams, and players at the same time while keeping game information organized. My job was to help design a web-based version of the game that could work across different platforms.

## Project Reflection

### What did you do particularly well in developing this documentation?

I think one thing I did well was comparing the different operating platforms and explaining their advantages and disadvantages. I looked at Windows, Linux, Mac, and mobile devices to see how each one could support the game. I also think I did a good job explaining why Linux would be a good choice for the server because it supports Java, works well for web applications, and can help reduce licensing costs. I tried to keep the explanations simple while still covering what the client needed to know.

### What about the design document was helpful when developing the code?

Working through the design document helped me understand how the different parts of the application were supposed to work together. The UML diagram was especially helpful because it showed how the Game, Team, Player, and GameService classes were connected. It also helped me understand why we used the Singleton pattern for GameService and how inheritance could reduce repeated code. Having the design planned out made it easier to understand what the code needed to do instead of just trying to figure everything out as I went.

### What would you revise, and how would you improve it?

If I could revise one part of the project, I would spend more time on the distributed systems and networking section. I explained how the game could use a central server and how players would connect through their browsers, but I think I could have gone into more detail about what happens when connections are lost. Since the game has timed rounds, I would want to make sure players could reconnect without losing their progress or getting out of sync with everyone else. I think spending more time on this would help prevent problems if players lose their connection during a game.

### How did you interpret and implement the user's needs?

I started by looking at what The Gaming Room wanted the application to do. They needed the game to work on multiple platforms, support different teams and players, and keep game information consistent. I used these requirements to help decide on a client-server design where the server would manage the game and players could connect through a web browser. I also considered storage, memory, and security because the game needs to load images quickly and protect player information. I think considering the user's needs is important because even if an application runs correctly, it won't be very useful if it doesn't do what the client actually wanted.

### How did you approach designing software, and what would you do in the future?

My approach was to first understand the requirements and then look at the different options for meeting them. I used the UML diagram to understand the relationships between classes and compared operating platforms before making a recommendation. I also considered how the game would handle multiple users, store information, and communicate over a network. In future projects, I would use a similar approach by starting with the requirements, planning the structure, and comparing different solutions before writing too much code. This project helped me understand why it is important to plan things out before starting to write code. I think having a design to follow makes it easier to know what needs to be done.
