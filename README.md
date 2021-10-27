# RCWGAN-GP

In material science, knowing what kind of microstructure will form under a certain set of processing parameters is an essential probblem. This is because the material's properties largely depend on the microstructure.

For example, in laser sintering ceramics, the grain size and porosity depends on the laser power. In general, with larger laser power, the grain gets larger and the porosity get lower. On the other hand, the hardness of the resulted material is inversely proportional to the grain size and the porosity. Thus, to obtain a hard piece of ceramic, the laser power needs to be carefully tuned.

Conventionally, knowledge about how the laser power affects the microstructure is obtained by trial-and-error experiments, which is labor-extensive and time-consuming. Using machine learning algorithm to estimate the microstructure based on processing parameters such as laser power could really accelerate process optimization and material design.

This figure illustrates the idea:

![](images/regress%20microstructure%20against%20processing%20parameter.png)

After training, the algorithm can predict microstructure under a new value of processing parameter that is not in the train set. Comparison between the synthesized micrographs and real micrographs is below:

![](images/alumina%20qualitative%20comparison.png)

A more close look into how the algorithm grasps the relationship between a processing parameter(laser power) and a microstructure:

![](images/regress%20alumina%20microstructure%20agianst%20laser%20power.png)

Details about the training data adn result discussion can be found in our paper: 

[Machine learning-based microstructure prediction during laser sintering of alumina](https://www.nature.com/articles/s41598-021-89816-x)
  
