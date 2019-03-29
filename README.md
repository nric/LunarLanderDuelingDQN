# LunarLanderDuelingDQN
A minimalistic tensorflow.keras (tf2.0) implentaion of a dueling DQN to solve the LunarLander-v2 gym env.


This is a simple implementation of a (Dueling) Deep Q learning agent tested on Open AI Gym's lunar lander.
It it has two major alogorithms included. : Deep Q Learning (DQN) and Dueling DQN (http://proceedings.mlr.press/v48/wangf16.pdf)
Change the self.model line if you want to use one or the other.
The dueling one eventually learned to land in my short testing series. The vanilla DQN just learned to hover stabel
I did not hyper parameter optimization what so ever. The saving has a bug, fix if you want to.
Code was run and tested in VS Code with Ipykernel interactive environment but if you change the un-comment
the __name__ == __main__ line it should. 
Requires Tensorflow >= 1.12, gym (please refer to openai gym homepage if packages are missing like cmake or swig)
