# Shower Temperature Reinforcement Learning

#### -- Project Status: Completed

## Project Intro/Objective
One of the problems in my current apartment is that the shower temperature fluctuates frequently. Especially if someone flushes the toilet. In this project, I wanted to simulate the fluctuating shower environment and see if I could build a reinforcement learning model with TensorFlow in order to keep the temperature within the desired range.

### Methods Used
* Deep Learning
* Reinforcement Learning
* Object Oriented Programming


### Technologies
* Python
* Pandas, jupyter
* TensorFlow, Keras
* DQNAgent
* BoltzmannQPolicy
* Sequential Memory

## Project Description
Although both supervised and reinforcement learning use mapping between input and output, reinforcement learning uses rewards and punishments as signals for positive and negative behavior. In this project, the RL model received a reward for keeping the shower temperature within the desired range (between 87 to 93 degrees fahrenheit) and a negative reward if it is not within the desired range. The shower length is 60 seconds, and every second the temperature can fluctuate by 1 degree upwards or downwards. The model has an action space composed of 5 actions. Every second, it can change the temperature by: (-2, -1, 0, 1, 2). I ended up building a Sequential model and using a DQNAgent, which is a value-based reinforcement learning agent that trains a critic to estimate the return or future rewards.


## Featured Notebooks/Analysis/Deliverables
* [Notebook](https://github.com/lukemonington/shower_temp_reinforcement_learning/blob/main/Shower%20Temperature%20Reinforcement%20Learning.ipynb)


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
