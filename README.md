# SB3-Gymnasium Samples

SB3-Gymnasium-Samples is a repository containing samples of projects involving AI Reinforcement Learning within the Gymnasium and Stable Baselines 3 tools. 
The projects in this repository were created using the official documentation for both tools, as well as adjustments and architecture that I thought were more elegant and comfortable.

The following links should redirect you to their respective documentation:

```Stable Baselines 3``` - https://stable-baselines3.readthedocs.io/en/master/

```Gymnasium``` - https://gymnasium.farama.org/index.html

##

The development of these projects involved some obstacles, especially regarding compatibility with the operating system.

If you want to run the Jupyter Notebooks contained in this repository on a Windows operating system, or even design new agents, I strongly recommend reading up on the peculiarities of compatibility with each operating system.

During development, ```Anaconda/Miniconda``` was used to manage the packages and work around incompatibilities.
- https://docs.conda.io/projects/conda/en/23.1.x/user-guide/install/windows.html

In addition, ```PyTorch``` was installed to train the agents. Within the project, you can find it in the dependencies section, but the exact installation may vary from one machine to another. You should therefore check the official documentation. 
- https://pytorch.org/

##

The implementation of the agents in this project was a success for various models and environments. Especially Atari environments with their endless range of game samples. Although not all agents were insightful in all environments, some were particularly impressive. 

The use of vectorized environments was particularly useful for training models in multiple parallel environments, greatly speeding up learning. 

![breakout-16-fps](https://github.com/Henrique-Bidarte/sb3-gymnasium-samples/assets/134324510/79628802-8187-4ada-8d08-33eaff771106)
- Breakout_v5
  
The samples for the Atari environments are contained in the folder with the respective name. The file can be duplicated and modified to act in other games. A little attention should be paid to the constants section within the project so that the necessary adjustments and changes can be made to each of the games.

##

A Box-2D environment is also contained in the sample. The Lunar Lander was one of the first Reinforcement Learning implementations I came across during my studies. Here, this environment is made available by Gymnasium and its implementation was made using the respective documentation.
This environment is very pleasant to watch during learning and, in my opinion, very elegant. 


