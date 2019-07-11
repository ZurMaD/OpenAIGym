# Introduction

# Project 5: Bipedal-Walker

- BipedalWalker has 2 legs. Each leg has 2 joints. You have to teach the Bipedal-walker to walk by applying the torque on these joints. You can apply the torque in the range of (-1, 1). Positive reward is given for moving forward and small negative reward is given on applying torque on the motors.

### Smooth Terrain

- In the beginning, AI is behaving very randomly. It does not know how to control and balance the legs.

<img src=bipedal-walker/training/1.gif width="400">

- After 300 episodes, it learns to crawl on one knee and one leg. This AI is playing safe now because if it tumbles then it gets -100 reward.

<img src=bipedal-walker/training/2.gif width="400">

- After 500 episodes it started to balance on both of the legs. But It still needs to learn how to walk properly.

<img src=bipedal-walker/training/3.gif width="400">

- After 600 episodes, it learns to maximize the rewards. It is walking in some different style. After all, it’s an AI not a Human. This is just one of the way to walk in order to get maximum reward. If I train it again, it might learn some other optimal way to walk.

<img src=bipedal-walker/training/4.gif width="400">

### Hardcore Terrain

- I saved my weight from the previous training on simple terrain and resumed my training on the hardcore terrain. I did it because the agent already knew how to walk on simple terrain and now it needs to learn how to cross obstacles while walking.

<img src=bipedal-walker/training/5.gif width="400">
