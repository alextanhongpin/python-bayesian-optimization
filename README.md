# python-bayesian-optimization
All about Bayesian Optimization

## References
- https://www.cs.ox.ac.uk/people/nando.defreitas/publications/BayesOptLoop.pdf

## Bayesian Optimization

Bayesian optimization is a sequential strategy for the global optimization of black-box functions, especially useful when the function is computationally expensive to evaluate[3]. It treats the objective function as a random function and places a prior over it, updating this prior as data is gathered to form a posterior distribution, which is then used to determine the next query point[3]. This method has found applications across various industries and research areas[2][3][4].

**Example Use Cases:**
*   **Robotics:** Bayesian optimization can optimize a robot's gait for objectives like velocity or smoothness. It has also been used in navigational tasks, helping robots minimize uncertainty about their location and map estimates while moving through environments[2]. In one instance, it was used to optimize the control parameters of a robot cleaning up liquid spills[2][5].
*   **Reinforcement Learning:** It is applied in hierarchical reinforcement learning to automatically tune parameters of neural network policies and learn value functions[1][2]. Additionally, it has been used to develop attention policies in image tracking using deep networks[1][2].
*   **Machine Learning and Hyperparameter Tuning:** Bayesian optimization automates the selection of the best model and its hyperparameters for a given problem, proving effective in tuning complex models like deep belief networks and convolutional neural networks[1]. It has also been beneficial in automating the selection process among models offered by machine learning libraries[1].
*   **A/B Testing:** In A/B testing, Bayesian Optimization enhances the efficiency of testing different product configurations, like ads or websites. It uses feedback from earlier tests to make informed decisions about which user subsets to query next, optimizing the product's overall performance while minimizing opportunity costs[1].
*   **Natural Language Processing:** Bayesian optimization automates the process of choosing the best way to represent text in NLP models, simplifying model development and enhancing overall performance[1].
*   **Facial Recognition:** Bayesian optimization has been applied in the field of facial recognition to optimize the Histogram of Oriented Gradients (HOG) algorithm parameters and image size using a Tree-structured Parzen Estimator (TPE) based Bayesian optimization technique[3].
*   **Combinatorial Optimization:** It can also be employed to tackle combinatorial optimization problems[2].
*   **Sensor Networks:** Sensor networks use Bayesian optimization to monitor environmentally relevant quantities such as temperature or concentration of pollutants[2].

Citations:
[1] https://www.datacamp.com/tutorial/mastering-bayesian-optimization-in-data-science
[2] https://www.cs.ox.ac.uk/people/nando.defreitas/publications/BayesOptLoop.pdf
[3] https://en.wikipedia.org/wiki/Bayesian_optimization
[4] https://arxiv.org/pdf/2206.03301.pdf
[5] https://www.repository.cam.ac.uk/items/e4af63b0-ed77-4cf2-b008-6226cfb43dff
[6] https://jmlr.csail.mit.edu/papers/volume20/18-225/18-225.pdf
