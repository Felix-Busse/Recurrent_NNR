# SpaceFlight-RNN
Make neuronal networks (here RNNs) learn on flight trajectories of space ships!

# Scope
Integrating the equation of motion is standard method to learn about the future flight path of space ship. As this is computational expensive, the idea is to train a neuronal network, that can predict the future flight path with much less effort. <br>
Therefore the [Jupyter-Notebook](space_ships_RNN.ipynb) in this repository offers classes to easily calculate a set of training data by integrating some equation of motion. The environment can be specified by placing one or more space bodies, which will act with their gravity on the space ship. Plot methods and functions allow visualizations of environment and trajectories.

# Contributions
In the notebook you find an example, where data of trajectories of satellites, being launchend in the vicinity of a planet was generated and used to train a net. See the good results and the plots. <br>
Feel free to search for new usecases, such as setting up problems with to bodies and a space ship (travel to moon). 

# How to contribute
 |Steps|
 |:----------------------|
 |- Fork this repository|
 |- Clone your repository|
 |- Create new training data for new case of space flight|
 |- Train a neuronal network on this data and visualize/evaluate|
 |- Commit and push|
 |- Create Pull request|
 |- Wait for merge|
