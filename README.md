# tf_agents_environment
Code an environment to be used with preset "car-pole" example found in:<br/>
https://github.com/tensorflow/agents/tree/master/tf_agents/colabs

The environment designed has 6 states (0-5) <br/>
from each state the agent has 4 apossible actions: <br/>
up, right, down, left<br/>
for each state/action pair the agent receive a reward based on the direction, shown below:

![environment](https://github.com/prevelat/tf_agents_environment/blob/master/Environment.png)<br/>

the episode ends with 1000 steps / actions or by reaching state 2
