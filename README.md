# SET
DQN with context bandit task (thanks to kind advice from geraudnt.github.io)</br>

This is the DQN network training with context bandit environment with the board game, SET.
After observing the three cards with four features, the agent come to judge whether they are valid sets or not. </br></br>
![alt text](https://github.com/SoanKim/SET/blob/main/result.png)

### Requirements</br>
matplotlib</br>
numpy>=1.11.0</br>
torch==0.4.0</br>
pandas</br>
scipy</br>
ipykernel</br>

### Future Work</br>
Feed the context in pixel</br>
Implementing [inverse propensity score](https://arxiv.org/pdf/1103.4601.pdf)
