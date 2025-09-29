DQN on Space Invaders

The initial DQN Pong notebook is modified for the Space Invaders Atari environment in this project.  
Two brief gaming movies that demonstrate the agent's development from early random play to later better conduct are shown.

Videos:
Early training (near-random policy):  
<video src="early_spaceinvaders.mp4" controls width="480"></video>

Later training (after brief training):  
<video src="later_spaceinvaders.mp4" controls width="480"></video>

Reflection:
Compared to some other Atari games, Space Invaders has a clear purpose and more regular rewards, which is why I selected it.  
 This helps illustrate how the agent picks up fundamental methods and makes it simpler to see progress following a brief training run.

 The spy walks and shoots largely at random in the first segment, missing the majority of targets and rapidly losing life.  
 The agent moves with a little more purpose after some training, frequently situating itself beneath the aliens and striking them more frequently in the subsequent clip.

 The fact that there are still not many rewards—the spy must learn that shooting aliens earns points—was one difficulty.  
 This made the initial learning process slower.

 
Additionally, I observed that the agent may further refine its approach and become more stable with additional training steps, a slower epsilon decay, and perhaps a bigger replay buffer.

 Overall, the experiment demonstrates that a brief training run is sufficient to yield observable behavioral improvements in the agent.
