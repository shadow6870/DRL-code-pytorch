# PPO-discrete
This is a concise Pytorch implementation of PPO on discrete action space with 10 tricks.<br />

# 10 tricks
Trick 1—Advantage Normalization.<br />
Trick 2—State Normalization.<br />
Trick 3 & Trick 4—— Reward Normalization & Reward Scaling.<br />
Trick 5—Policy Entropy.<br />
Trick 6—Learning Rate Decay.<br />
Trick 7—Gradient clip.<br />
Trick 8—Orthogonal Initialization.<br />
Trick 9—Adam Optimizer Epsilon Parameter.<br />
Trick10—Tanh Activation Function.<br />

## Test environments
You can set the 'env_index' in the codes to change the environments. Here, we test our code in 2 environments.<br />
env_index=0 represent 'CartPole-v1'<br />
env_index=1 represent 'LunarLander-v2'<br />


## Training result
![image] 