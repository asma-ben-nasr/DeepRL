# Reinforce-PPO
This is a repository containing REINFORCE and PPO algorithms implemented using Pytorch
## Use REINFORCE and PPO for the Cartpole v-0 env
![cartpole](/poster.jpg?raw=true "Optional Title")
### Requirements installation
First Download or clone the repository.
Then pip install requirements.txt using
```` 
pip install -r requirements.txt
```` 
### For REINFORCE
Go into the jupyter notebook and run it all
### REINFORCE Results
This is a plot of score by the number of episodes
![reinforce](/output_reinforce.png?raw=true "Reinforce score")

### For PPO
Navigate into the ppo folder and run the jupyter notebook train.ipynb
PS: the actor and critic networks are already trained in the repository. you can skip the training and see the execution right away.
### PPO results
This is a plot of average score by the number of episodes
![ppo](/output_ppo.png?raw=true "PPO average score")


### Execution on Cartpole v-0
Here is an example of execution of REINFORCE algorithm.
![](results.gif)
