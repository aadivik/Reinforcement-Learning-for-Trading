# Reinforcement-Learning-for-Trading


Reinforcement Learning
Reinforcement learning is a type of machine learning where there are environments and agents. These agents take actions to maximize rewards. Reinforcement learning has a very huge potential when it is used for simulations for training an AI model. There is no label associated with any data, reinforcement learning can learn better with very few data points. All decisions, in this case, are taken sequentially. The best example would be found in Robotics and Gaming.

Q – Learning
Q-learning is a model-free reinforcement learning algorithm. It informs the agent what action to undertake according to the circumstances. It is a value-based method that is used to supply information to an agent for the impending action.  It is regarded as an off-policy algorithm as the q-learning function learns from actions that are outside the current policy, like taking random actions, and therefore a policy isn’t needed.

Q here stands for Quality. Quality refers to the action quality as to how beneficial that reward will be in accordance with the action taken. A Q-table is created with dimensions [state,action].An agent interacts with the environment in either of the two ways – exploit and explore. An exploit option suggests that all actions are considered and the one that gives maximum value to the environment is taken. An explore option is one where a random action is considered without considering the maximum future reward.

Matrix q-learning

 Reinforcement Learning Automated trading q learning formula

Q of st and at is represented by a formula that calculates the maximum discounted future reward when an action is performed in a state s.

The defined function will provide us with the maximum reward at the end of the n number of training cycles or iterations.

Trading can have the following calls – Buy, Sell or Hold

Q-learning will rate each and every action and the one with the maximum value will be selected further. Q-Learning is based on learning the values from the Q-table. It functions well without the reward functions and state transition probabilities.

 

