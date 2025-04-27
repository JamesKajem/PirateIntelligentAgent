The code provided was the framework of a maze game. 
This included an agent, its movement, and an environment in which to move around in.

I programmed the full qtrain function & loop for deep learning. 
The model trains for 1499 epochs, then summarizes the results* and later presents the (ideally) completed maze.
It loops over each epoch, and calculates the total loss with each episode, totalling in a win count and win rate that is then output as a string. 
The real trick I found in this design was to change the agent spawn location on each replay.
This throws the Exploration vs Exploitation balance on its head, but overall vastly increases the rate at which the agent will explore its environment.

Approximation is a difficult thing to program, and coding elements of a decision-making process was one of the most interesting things I have ever interacted with in computer science.
The ability to decide what is by what isn't is not a simple equation, and that equation needs to be calculated along a trajectory in attempt of mirroring a constant, whether that be time, reality, or in this case; 1499 epochs.
Binary takes thousands of opportunities of declaring true or false before anything complicated can ever be determined, and approximation is just the reiteration of this fact until it reaches a percentage that we are satisfied with.
The nature of approximation is fundamentally flawed, and mathematically cannot ever be 100% accurate, leading to an exponential decay of any learning process. 
This is a fact that neural network technology will never escape from, it is a foundational flaw within the core math of its decisions.
It is facts like these that show that AI doesn't really 'think' - it approximates, which is a much simpler process.
