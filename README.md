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

![BreakOut](https://github.com/Henrique-Bidarte/sb3-gymnasium-samples/assets/134324510/663e0479-c4e5-4935-8df3-706aff8233d7)

- Breakout_v5
  

##

A Box-2D environment is also contained in the sample. The Lunar Lander was one of the first Reinforcement Learning implementations I came across during my studies. Here, this environment is made available by Gymnasium and its implementation was made using the respective documentation.
This environment is very pleasant to watch during learning and, in my opinion, very elegant. 

![Lunar-Lander](https://github.com/Henrique-Bidarte/sb3-gymnasium-samples/assets/134324510/42c5884c-4cdf-47e2-a532-161ea0c39a08)

- Lunar_Lander_v2

##

It is possible to control the projects flow through the ```constants``` section in the Jupyter Notebooks. Not only it assigns values ​​to the different variables consumed, but it indicates whether the project should generate a new model for experimentation or train an existing one.

Logs will be saved within the ```logs``` folder so they can be analyzed accordingly.

Trained models are saved in the ```models``` folder alongside the number of steps executed in the training.

The project has an option to load a best_model file. This must be named as in its respective constant, and made available in the root folder of each of the files.

