# Deep-Reinforcement-Learning
Deep Reinforcement Learning Assignment, Spring 2022, Tilburg University, Department of Cognitive Science and Artificial Intelligence

The assignment was composed of two parts. In the first part, the effect of changing the reward function in a simplified self-driving car environment was explored. In the second part, tasks involving Imitation Learning and Behavior Cloning were investigated. 

## Part 1
The different reward configurations resulted in three distincs agents. 

![alt text](data:image/jpeg;base64,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)

![alt text]([https://www.pngwing.com/en/search?q=fillmore](https://w7.pngwing.com/pngs/437/73/png-transparent-car-volkswagen-type-2-fillmore-lightning-mcqueen-car-van-car-mode-of-transport-thumbnail.png))
