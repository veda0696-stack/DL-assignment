# DL-assignment
1. Cats vs Dogs CNN (Image Classification)

The original CNN code was modified to improve optimization by incorporating data normalization, minimizing unnecessary computation, and stabilizing the learning process. The model architecture remained simplified but optimized by layering both convolution and pooling to avoid overfitting. Unnecessary plotting statements, manual stopping of processes, and repetition in code statements were eliminated to enhance efficiency in code execution and readability.

2. AlexNet Architecture

The AlexNet model was optimized by minimizing the parameters in the fully connected layers and applying Batch Normalization. The Functional API approach was used in lieu of a subclassed Sequential model for better flexibility and readability. These modifications greatly reduced memory usage while retaining the essence of the AlexNet model, making it ideal for student projects and resource-constrained environments.

3. Graph-Based Reinforcement Learning (Q-Learning Path Finding)

The Q-learning program was optimized for reinforcement learning by simplifying the construction of the reward matrix, preventing the repetition of function definitions, and enhancing the action choice logic. The naming of variables was made consistent, and unnecessary loops were eliminated for optimization. The modified program improves the efficiency of the Q-learning process while preserving the same learning behavior and output courses.

4. LSTM Time Series Prediction (Airline Passengers)

The time series model based on the LSTM architecture has been optimized. This has been done by ensuring proper data processing and input format. The training process has been ensured to be stable with optimal batch size. Unnecessary imports have been removed. The split for training and testing has been made clean.

5. RNN Text Generation

The SimpleRNN for the generation of texts was optimized by improving the way sequences are handled, by applying proper methods for handling one-hot, and by making sure that the dimensions are properly aligned when predicting sequences. Handling of activation functions and sizes was properly selected to ensure there was a balance between learning and overfitting.

6. Tic-Tac-Toe The code optimization for the Tic-Tac-Toe Reinforcement Learning involved the correction of initialization errors, elimination of illogical statements, and improvement in the reward propagation statements. Unnecessary checks were eliminated, there was clearance in the handling of exploration and exploitation, and the code organization was made more modular.
