# Deep-RL-Navigation

## The Environment
This project featured an agent learning to navigate and collect bananas in a Unity simulated environment. The agent was trained in a reinforcement learning framework, where the agent had actions to move forward, backward, left or right, and received +1 reward for collecting yellow bananas and -1 reward for collecting blue bananas.

The environment is considered solved when the agent has learned a policy that receives an average reward of 13 over 100 episodes.

To run the code, go to `Navigation.ipynb`.

See Report.pdf for more information on the environment, the learning algorithm, results, and ideas for future work.

## Useage Instructions
To run the environment:

* Follow the instructions to install the ML-Agents package from Unity - Technologies [here](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)

* Install the following Python packages:
  * tensorflow==1.7.1
  * Pillow>=4.2.1
  * matplotlib
  * numpy>=1.11.0
  * jupyter
  * pytest>=3.2.2
  * docopt
  * pyyaml
  * protobuf==3.5.2
  * grpcio==1.11.0
  * torch==0.4.0
  * pandas
  * scipy
  * ipykernel

* Download the Unity Environment from the appropriate link listed here:
  * Linux: click [here] https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
  * Mac OSX: click [here] https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip
  * Windows (32-bit): [click here] https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip
  * Windows (64-bit): [click here] https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip
  
* Then, place the file in the p1_navigation/ folder in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) , and unzip (or decompress) the file

* After you have followed the instructions above, open Navigation.ipynb (located in the p1_navigation/ folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.

