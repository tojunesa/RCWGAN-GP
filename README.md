# RCWGAN-GP

<p>In material science, knowing what kind of microstructure will form under a certain set of processing parameters is an essential probblem. This is because the material's properties largely depend on the microstructure. <p>
<p>For example, in laser sintering ceramics, the grain size and porosity depends on the laser power. In general, with larger laser power, the grain gets larger and the porosity get lower. On the other hand, the hardness of the resulted material is inversely proportional to the grain size and the porosity. Thus, to obtain a hard piece of ceramic, the laser power needs to be carefully tuned.<p>
<p>Conventionally, knowledge about how the laser power affects the microstructure is obtained by trial-and-error experiments, which is labor-extensive and time-consuming. Using machine learning algorithm to estimate the microstructure based on processing parameters such as laser power could really accelerate process optimization and material design.<p>
<p>The following code trains a Regression-based Conditional Wasserstein Generative Adversarial Network. It takes in processing parameters to estimate the resulted material's microstructure.<p>
  
