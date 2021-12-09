# USE OF LEARNED OPTIMISERS IN COMPUTER VISION

### You can find an implementation the learning to learn by gradient descent by gradient descent using TensorFlow v2+ in the above folders

Feel Free to contribute 

### Abstract
Machine learning approaches have emerged as the preferred approach for developing computer vision
solutions. Despite the success of learned features in machine learning, optimization algorithms are
still designed by hand. The design of gradient-based optimization algorithms for neural networks
such as RMSProp, Adam and SGD as well as adapting optimizer parameters to suit a particular
problem, have been researched significantly. However, in recent years, there has been an emerging
field of interest in machine learning called meta-learning. The objective of meta-learning is to enable
models to learn from a limited number of experiences very quickly, adapt to novel tasks and to build
models that generalise better. One of the objectives of this project is to implement the meta-learning
method called "Learning to learn by gradient descent by gradient descent"[3] which has shown that
optimizers can be learned automatically using LSTM recurrent neural networks and be generalised
to new problem domains with similar network architectures. The aim of the project is first, to
develop the model in TensorFlow to get a greater understanding of how meta-learning works, as well
as transparency (code will be posted on GitHub) and usability. At every stage of the project the
performance of the meta-learner is critically analyzed and compared against standard hand crafted
optimizers. Additionally, the project explores the application of learnt optimizers in computer
vision tasks on well known datasets, where more complex machine learning architectures are used
to solve a particular problem. The project takes into account the training time of the algorithms,
complexity as well as the algorithm’s suitability in the chosen domain. Finally, the project examines
the application of the learned optimizer to a model that utilizes the Spatial Transformer Network [16]
to learn how to geometrically correct an input image to fit a given example image and test how well
the project generalises. In this research I show that learning to learn can be used to optimize neural
networks for computer vision tasks. However, tuning the meta-learner’s hyper-parameters has been
significantly challenging, thus achieving exceptional results has been difficult. This study identifies
the fields that have had the most impact on the meta-learner’s performance and suggests potential
areas for researchers to explore. This will increase the learned optimizer’s efficiency and could
eventually replace conventional optimizers in machine learning, especially in the field of computer
vision, where model generalisation is critical.
