# Snake Game

A classic [Snake](https://en.wikipedia.org/wiki/Snake_(video_game_genre)) game played by an AI trained using [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning). This game is based on the tutorial [Python Engineer](https://github.com/python-engineer) created [here](https://www.youtube.com/playlist?list=PLqnslRFeH2UrDh7vUmJ60YrmWd64mTTKV). 

## How To Run

Install all dependencies for this game
```
pip3 install -r requirements.txt
```

Start game with:
```
python3 agent.py
```

## Concepts and Technologies

### **- Reinforcement Learning**
A machine learning model that trains an agent in an environment where each action it makes is to maximize its total reward.

### **- 'Deep' Q-Learning**
At every step, we calculate a Q-value based on the current action and correspoding reward plus the maximum Q-value from the next actions.  

### **- PyTorch**
An open source machine learning framework, provides packages for various useful functions such as Linear and Optimization functions. 

### **- matplotlib**
Plotting library to plot highest and mean score of the AI. 