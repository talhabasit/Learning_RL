# Learning_RL

- Stable baselines
- Pytorch RL

## FMDP (Finite Markov Decision Processes)

- Discrete action spaces 
- the env returns conditional Probs which are dependent on the current state action and Reward 
- the probs have to add up to 1 
- **Markov Property**: No dependence to the conditioal prob on the past just the current state and the Action 
- pi is the policy 
- Conditional Prob -> represents the prob of taking an action given the current state
- **Expected return**: sum/ cumulative reward of all the future rewards
- Discounting factor in range [0,1] controls how far sighted the agent is
- Greediness of the agent
- **Value Function**: Reward expected from taking an action being in the current state
using the chosen policy that dictates the action that has to be taken also **Q-Value**

## Bellman equation
- Bellman equation result in the optimal Q value

