# Physics-informed neural network

New approach to solving problems in computational phsyics using deep learning. Integrates the prijnciples of physics, often expressed in the form of differential equations, direcly into the architecture of neural Networks. 

### 1. Combining Physical Laws with Machine Learning: 
Traditional neural networks learn patterns and relationships from data. PINNs on the otherhand, are trained not just on data bt also on the underlying physical laws governing the topic being studied. This is done by incorporating the governign differential equations into the loss function of the neural network. 

### 2. Structure of a PINN
* Input Layer: Takes input paramenters 
* Hidden Layer: Multiple layers where computations and feature extractions occur. 
* Output Layer: Gives the solutoin to the probelm, which could be values of a phusical field. 
* Loss function: The loss funciton in a PINN includes terms that represent the deviation of the network's outputs from both the available datea and the governing phuysical laws 

### 3. Advantages: 
*Data Effciency: 
*Generalizability: They are better at generalizing beyond the range of the training data, thanks to the embedded physical laws.
*Interpretable and Reliable: Incorporation of known physical laws makes the network's predictions more interpretable and reliable.

### 4. Applications:

Solving Complex Equations: They are particularly useful in scenarios where the solution of complex differential equations is needed but difficult to obtain through traditional numerical methods.
Engineering and Sciences: PINNs find applications in fluid dynamics, material science, climate modeling, and more.
Healthcare: In medical imaging and modeling biological processes.

### 5. Challenges:

*Computational Complexity: The inclusion of differential equations in the training process can make PINNs computationally intensive.
*Designing Loss Functions: Crafting a loss function that appropriately balances data fidelity and physical law adherence can be challenging.

### 6. Future Prospects: 
As computational power increases and methods for efficiently training such networks improve, the use and effectiveness of PINNs are expected to grow, enabling more accurate and efficient modeling and prediction in various scientific and engineering fields.

In summary, Physics-Informed Neural Networks represent a fusion of deep learning and physical science, offering a powerful tool for solving complex problems where traditional methods fall short. They are poised to play a significant role in advancing research and applications across various scientific disciplines.


Here is an article where [PINN is applied to a plane stress problem]https://medium.com/dataseries/solving-plane-stress-problem-by-using-physics-informed-neural-network-fb018620402c